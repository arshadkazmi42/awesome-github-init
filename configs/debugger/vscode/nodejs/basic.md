## Mocha Debug Config

Copy the below config and paste in `launch.json` of your `VS Code`.
Add breakpoints and start debugger.

```json
{
  // Use IntelliSense to learn about possible attributes.
  // Hover to view descriptions of existing attributes.
  // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "Launch Program",
      "program": "${file}" // Change it to your entry point js file (Eg: index.js)
    }
  ]
}
```