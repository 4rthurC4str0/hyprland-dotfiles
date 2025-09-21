# hyprland-dotfiles
Minhas configurações de dotfiles para hyprland com arch linux

## Tema do SDDM
https://github.com/Keyitdev/sddm-astronaut-theme

### Instalação automática
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/keyitdev/sddm-astronaut-theme/master/setup.sh)"
```
## inspiração da waybar
https://github.com/elifouts/Dotfiles

```sh
{
    "security.workspace.trust.banner": "never",
    "security.workspace.trust.startupPrompt": "never",
    "chat.disableAIFeatures": true,
    "workbench.startupEditor": "none",
    "explorer.compactFolders": false,
    "workbench.iconTheme": "material-icon-theme",
    "code-runner.executorMap": {
        "python": "clear ; python3 -u"
    },
    "code-runner.runInTerminal": true,
    "code-runner.ignoreSelection": true,
    "workbench.colorTheme": "Dracula Theme",
    "security.workspace.trust.untrustedFiles": "open",
    "files.autoSave": "afterDelay",
    "editor.fontFamily": "'JetBrainsMono Nerd Font', 'Droid Sans Mono', 'monospace', monospace",
    "python.defaultInterpreterPath": "/bin/python"
}

```