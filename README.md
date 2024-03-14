## show app switcher on all displays

```
defaults write com.apple.Dock appswitcher-all-displays -bool true; killall Dock
```

## install xcode

either install full package through app store or just install xcode command line tools via `xcode-select --install`

## install [brew](https://brew.sh/)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## install [hyper](https://hyper.is/) and [iterm2](https://iterm2.com/)

`brew install --cask hyper`  
`brew install --cask iterm2`

[hyper settings and plugins](./hyper.js)  
[iterm profiles](./iterm2-profiles.json)

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
fastfetch
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
zoom
1kc-razer
sonos
pictogram
monitorcontrol
```

`xargs brew install --cask < apps.txt`

## install vscode extensions and settings

[https://github.com/thejoshchow/vscode-settings](https://github.com/thejoshchow/vscode-settings)
