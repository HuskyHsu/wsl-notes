# awesome-wsl

## Install

1. [wsl install in win10](https://docs.microsoft.com/zh-tw/windows/wsl/install-win10)
2. [install windows-terminal](https://www.microsoft.com/zh-tw/p/windows-terminal/9n0dx20hk701)
3. [install powershell](https://aka.ms/powershell-release?tag=preview)
4. [使用系統管理員身分開啟 Windows Terminal 分頁](https://blog.poychang.net/run-windows-terminal-as-administrator-with-elevated-admin-permissions/)
```json
# use PowerShell core
{
  "guid": "{1c51715d-2aa5-4f7a-a3d1-1ec081a1ef36}",
  "name": "PowerShell Elevated",
  "commandline": "gsudo.exe pwsh.exe",
  "hidden": false,
  "fontFace": "MesloLGS NF",
  "colorScheme": "One Half Dark",
  "icon" : "https://i.imgur.com/asceJXS.png"
}
```

```zsh
# into wsl
USERNAME@DESKTOP > wsl
/mnt/c/Users/USERNAME > lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 20.04.2 LTS
Release:        20.04
Codename:       focal
```

## Development Environment

0. [install git](https://git-scm.com/downloads) or [git of chocolatey](https://chocolatey.org/packages/git)
1. [使用 oh-my-posh 美化 PowerShell 樣式](https://blog.poychang.net/setting-powershell-theme-with-oh-my-posh/)
2. [用 zsh + zim + powerlevel10k 讓你的 Terminal 潮又快](https://dwy6626.github.io/post/zsh-zim-powerlevel10k/)
3. [vscode](https://code.visualstudio.com/download)
4. [vscode tool: Remote - Containers](https://docs.microsoft.com/zh-tw/windows/wsl/tutorials/wsl-vscode)

---

### Python

* [wsl-setup-vs-code-for-python-developmen](https://manojchoudhari.wordpress.com/2020/09/24/wsl-setup-vs-code-for-python-development/)

### Node.js

* [use nvm to manager node](https://github.com/nvm-sh/nvm)
