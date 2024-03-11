## install xcode

## install [brew](https://brew.sh/)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## install [hyper](https://hyper.is/)

```
brew install --cask hyper
```

[hyper settings and plugins](./hyper.js)

## install [omz](https://ohmyz.sh/)

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

**install [powerlevel10k](https://github.com/romkatv/powerlevel10k)**

- install MesloLGS NS font family
- copy [config](./p10k.zsh) into root directory

## install dev envs

`brew install nvm`  
`brew install openjdk`  
`brew install --cask miniconda`

## omz plugins

plugins.txt

```
zsh-autocomplete
zsh-autosuggestions
zsh-syntax-highlighting
thefuck
zoxide
fzf
```

1. `xargs brew install < plugins.txt`
2. run fzf install script
3. copy [zshrc](./zshrc)

## install apps

apps.txt

```
arc
homebrew/cask-versions/google-chrome-dev
homebrew/cask-versions/firefox-developer-edition
reflex
aldente
istat-menus
notion
notion-calendar
spotify
visual-studio-code
slack
docker
discord
hiddenbar
raycast
scroll-reverser
cursr
```

`xargs brew install --cask < apps.txt`

## install vscode extensions and settings

[https://github.com/thejoshchow/vscode-settings](https://github.com/thejoshchow/vscode-settings)
