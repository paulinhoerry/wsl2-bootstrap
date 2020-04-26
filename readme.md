## Installations

### WSL Setup

[Install]('https://docs.microsoft.com/pt-br/windows/wsl/wsl2-install')

### Softwares

#### VS Code

 - [Download]('https://code.visualstudio.com/download')
 - Sync
 - Material Theme Icons
 - Monokai Pro

#### Windows terminal

 - [Download]('https://github.com/microsoft/terminal')
 - [Materialshell]('https://github.com/carloscuesta/materialshell')

### Packages

#### Essencial dependencies
```
sudo apt update
sudo apt install dpkg-dev build-essential  python-dev python3-dev
```

#### Essencial packages

##### ZSH
```
sudo apt install zsh
```

##### Oh my zsh
[Install]('https://ohmyz.sh/#install')
[zsh-nvm]('https://github.com/lukechilds/zsh-nvm')

```shell
// .zshrc

ZSH_THEME="materialshell"
plugins=(git ssh-agent zsh-nvm)
```
