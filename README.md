# Personal Environment

Configuration for setting up my local environment on Windows.

## WSL
### WSL Backup

[Backup and restore before migrating to a new computer.](https://aalonso.dev/blog/how-to-back-up-and-restore-o-migrate-to-a-new-computer-a-wsl2-machine-481m)

### Oh My Zsh w/ Powerlevel10k
1. [Install oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh#basic-installation)
2. [Install Powerlevel10k](https://github.com/romkatv/powerlevel10k#getting-started)
3. [Install autojump](https://github.com/wting/autojump#installation)
4. Download zsh-autosuggestions by  
`git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`
5. Download zsh-syntax-highlighting by  
`git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`
6. Add plugins to .zshrc file:
```text title=/home/<user>/.zshrc
plugins=(
    docker
    docker-compose
    git
    zsh-autosuggestions
    zsh-syntax-highlighting
    autojump
    yarn
    dotnet
)
```

## ESlint and Prettier Setup for React w/ TypeScript

Easily set up ESlint and Prettier for project and VS Code with [eslint-config-philitician](https://github.com/Philitician/eslint-config-philitician).

## VS Code

### Settings sync

Enabling settings sync allows me to sync VS Code configuration across devices.

The following data are synchronized across devices:
1. Settings
2. Keyboard Shortcuts
3. User Snippets
4. Extensions
5. UI State


## JetBrains IDEs

### Settings sync

Settings are synchronized across devices by user account by  
`File -> Manage IDE Settings -> Sync Settings to JetBrains Account..`