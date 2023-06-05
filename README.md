# Table of Contents

- [FavTools](#favtools)
  - [Dev Tools](#dev-tools)
  - [Terminal](#terminal)
    - [iTerm settings](#iterm-settings)
  - [Themes](#themes)
  - [CLI Tools](#cli-tools)
  - [Applications](#applications)
  - [Chrome Extensions](#chrome-extensions)
  - [Chrome Search Engines](#chrome-searchengines)
  - [Git Aliases](#git-aliases)

# FavTools
This repo has all my favorite and recommended tools for Mac

## Dev Tools

```sh
# xcode - https://mac.install.guide/commandlinetools/index.html
xcode-select --install

# brew - https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Terminal
```sh
# iterm2 - https://iterm2
brew install iterm2 --cask

# zsh - https://www.zsh.org/
brew install zsh

# oh-my-zsh - https://ohmyz.sh/
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# warp - https://www.warp.dev/ 
brew install --cask warp
```

### Iterm settings:
Hotkey<br/>
Perferences -> Keys -> Hotkey<br/><br/>
Native key mappings<br/>
Perferences -> Profile -> Keys -> Key Mappings -> Presets... -> Native<br/>

## Themes

```sh
# powerlvl10k - https://github.com/romkatv/powerlevel10k
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

## CLI Tools
```sh
# tig - https://github.com/jonas/tig
brew install tig

# tldr - https://tldr.sh/
brew install tldr

# fzf - https://github.com/junegunn/fzf
brew install fzf
$(brew --prefix)/opt/fzf/install

# z - https://github.com/agkozak/zsh-z
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z

# zsh-autosuggestions - https://github.com/zsh-users/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# fx - https://github.com/antonmedv/fx
brew install fx

# lvim - https://www.lunarvim.org/docs/installation
LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)

# bat - https://github.com/sharkdp/bat
brew install bat

# exa - https://the.exa.website/
brew install exa
alias ls="exa"
```

## Applications

```sh
# chrome
brew install --cask google-chrome

# jetbrains toolbox
brew install --cask jetbrains-toolbox

# vscode - https://code.visualstudio.com/
brew install visual-studio-code --cask

# rectangle - https://rectangleapp.com/
brew install --cask rectangle

# meetingbar - https://github.com/leits/MeetingBar
brew install meetingbar

# spotify - https://www.spotify.com/
brew install --cask spotify

# maccy - clipboard manager https://maccy.app/
brew install --cask maccy

# raycast - https://raycast.com/
brew install --cask raycast

# cheatsheet - https://www.mediaatelier.com/CheatSheet/
brew install --cask cheatsheet
```

## Chrome Extensions

```sh 
# Vimium
https://chrome.google.com/webstore/detail/dbepggeogbaibhgnhhndojpepiihcmeb 

# Viewer devtools
https://chrome.google.com/webstore/detail/aahcojdfiikihlpfamimldmionifllkl
# Wix Insiders
https://chrome.google.com/webstore/detail/aofifmijnohoiikidmmhdohgjipaflak 
# iWix Extension
https://chrome.google.com/webstore/detail/ejfdniofoaeobdncklagejfcnfajnpgc
# Wix Statics Override
https://chrome.google.com/webstore/detail/fhaehbcdbkccakpjgokgppjkggkmkmbl 
# Wix Petri Sidekick
https://chrome.google.com/webstore/detail/hpdjckcenihbjfmaccadiaighajcjope
# WIX BI Monitor
https://chrome.google.com/webstore/detail/kpdeoodecbpgceddpmamibmgbbojjhjm

# Node.js V8 --inspector Manager (NiM)
https://chrome.google.com/webstore/detail/gnhhdgbaldcilmgcpfddgdbkhjohddkj 
# Redux DevTools
https://chrome.google.com/webstore/detail/lmhkpmbekcpmknklioeibfkpmmfibljd
# React Developer Tools
https://chrome.google.com/webstore/detail/fmkadmapgofadopljbjfkapdkoienihi

# X-Seen-By
https://chrome.google.com/webstore/detail/fgbigkhiiddfchdehilplnapalobfjei
# Url Editor PRO
https://chrome.google.com/webstore/detail/maoigfcibanjdgnepaiiadjhgmejclea
# Requestly
https://chrome.google.com/webstore/detail/mdnleldcmiljblolnjhpnblkcekpdkpa
# Proxy SwitchyOmega
https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif
# EditThisCookie
https://chrome.google.com/webstore/detail/fngmhnnpilhplaeedifhccceomclgfbg 
# JSON Viewer
https://chrome.google.com/webstore/detail/gbmdgpbipfallnflgajpaliibnhdgobh

# Better Pull Request for GitHub
https://chrome.google.com/webstore/detail/nfhdjopbhlggibjlimhdbogflgmbiahc
# Refined GitHub
https://chrome.google.com/webstore/detail/hlepfoohegkhhmjieoechaddaejaokhf
# OctoLinker
https://chrome.google.com/webstore/detail/jlmafbaeoofdegohdhinkhilhclaklkp 

# Web Vitals
https://chrome.google.com/webstore/detail/ahfhijdlegdabablpippeagghigmibma 
```

## Chrome SearchEngines
Either [Annie-bunny](https://github.com/snirsh-wix/annie-bunny)<br/>
Or chrome://searchEngines
```sh
# Backoffice
https://bo.wix.com/?q=%s

# Wix-life
https://www.wix-life.com/search?q=%s

# GitHub wix-private
https://github.com/search?q=%s+org%3Awix-private
```

## Git aliases
```sh
 [alias]
     masterbase = !git fetch && git rebase origin/master && git push --force-with-lease
     lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
     co = checkout
     unstage = reset HEAD
     graph = log --all --graph --decorate --oneline
     undo = reset HEAD~1
     yarnshmock = "!f() { git checkout origin/master -- yarn.lock && yarn && git add yarn.lock && git commit -m 'Resolve yarn.lock conflict by accepting master branch version and running yarn' && git push;}; f"
 ```
