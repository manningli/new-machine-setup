# New Machine Setup

My personal preferences when setting up a new machine. Documenting so I can at least remember the most common tasks.

## Settings

- Settings > Personalization > Colors > Choose your mode = Dark
- Settings > Personalization > Colors > Accent color = Automatic

## Installs

- [ ] Install [CaskaydiaCove Nerd Font](https://www.nerdfonts.com/font-downloads)
- [ ] Install PowerShell

```PowerShell
winget install --id Microsoft.Powershell --source winget
```

- [ ] Make PowerShell the default in Windows Terminal
- [ ] Turn on command suggestions: `Set-PSReadLineOption -PredictionSource History`
- [ ] Set CaskaydiaCove as the default terminal font
- [ ] Install Oh My Posh

```PowerShell
winget install JanDeDobbeleer.OhMyPosh -s winget
```

- [ ] Set Oh My Posh theme
  - [ ] Download [custom profile](https://gist.github.com/manningli/322d8fee07dc364cb2068ccf82b695de)
  - [ ] Open PS profile in Notepad: `notepad $PROFILE`
  - [ ] Paste:

```PowerShell
Import-Module Terminal-Icons
oh-my-posh init pwsh --config ~/Oh-My-Posh/slimfat-custom.omp.json | Invoke-Expression
```

- [ ] Install Git: `winget install --id Git.Git --source winget`
- [ ] Install NVM for Windows: `winget install --id CoreyButler.NVMforWindows --source winget`
- [ ] Install Notepad++: `winget install --id Notepad++.Notepad++ --source winget`
- [ ] Install [Visual Studio](https://visualstudio.microsoft.com/downloads/)
- [ ] Install [Visual Studio Code](https://code.visualstudio.com/download)
- [ ] Install [SQL Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms)
- [ ] Install [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install)

## VS Code Extensions

- GitLens
- markdownlint
- Prettier - Code formatter
- vscode-icons
