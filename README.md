# Satisfying Command

## WSL (Windows Subsystem for Linux)

- Shutdown, unregister, install.

  ```
  wsl --shutdown
  wsl --unregister Ubuntu
  wsl --install Ubuntu
  ```

Source(s):

- [Basic commands for WSL | Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/basic-commands)

## Visual Studio Code

- Remove user data

  ```
  Remove-Item -Path $env:APPDATA\Code -Recurse
  Remove-Item -Path $env:USERPROFILE\.vscode -Recurse
  ```

Source(s):

- [Uninstall Visual Studio Code](https://code.visualstudio.com/docs/setup/uninstall#_clean-uninstall)
