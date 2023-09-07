# Satisfying Command

## WSL (Windows Subsystem for Linux)

- Shutdown, unregister, install.

  ```
  wsl --shutdown
  wsl --unregister Ubuntu
  wsl --install Ubuntu
  ```

- Update and upgrade packages

  ```
  sudo apt update && sudo apt upgrade -y
  ```

Source(s):

- [Basic commands for WSL | Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/basic-commands)
- [Set up a WSL development environment | Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/setup/environment#update-and-upgrade-packages)

## Visual Studio Code

- Remove user data

  ```
  Remove-Item -Path $env:APPDATA\Code -Recurse
  Remove-Item -Path $env:USERPROFILE\.vscode -Recurse
  ```

- Install extension

  ```
  code --install-extension ms-vscode-remote.remote-wsl
  ```

Source(s):

- [Uninstall Visual Studio Code](https://code.visualstudio.com/docs/setup/uninstall#_clean-uninstall)
- [Managing Extensions in Visual Studio Code](https://code.visualstudio.com/docs/editor/extension-marketplace#_command-line-extension-management)
