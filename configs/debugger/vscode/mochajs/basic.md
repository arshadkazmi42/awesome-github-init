## Mocha Basic Debug Config

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
      "name": "Mocha Tests",
      "program": "${workspaceFolder}/node_modules/mocha/bin/_mocha",
      "args": [
        "${workspaceFolder}/test" // Test directory 
      ],
      "internalConsoleOptions": "openOnSessionStart"
    }
  ]
}
```