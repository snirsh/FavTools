# FavTools

This repository contains a curated list of my favorite and recommended tools for macOS. It includes software for development, terminal emulators, themes, CLI tools, applications, Chrome extensions, search engines, and Git aliases.

## Table of Contents

- [Dev Tools](#dev-tools)
- [Terminal](#terminal)
- [Themes](#themes)
- [CLI Tools](#cli-tools)
- [Applications](#applications)
- [Chrome Extensions](#chrome-extensions)
- [Chrome Search Engines](#chrome-search-engines)
- [Git Aliases](#git-aliases)

## Dev Tools

- Xcode - [Installation Guide](https://mac.install.guide/commandlinetools/index.html)
    ```sh
    xcode-select --install
    ```

- brew - [Official Website](https://brew.sh/)
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

## Terminal

- iterm2 - [Official Website](https://iterm2.com)
    ```sh
    brew install --cask iterm2
    ```
  
- zsh - [Official Website](https://www.zsh.org/)
    ```sh
    brew install zsh
    ```

- Oh-my-zsh - [Official Website](https://ohmyz.sh/)
    ```sh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    ```

- Warp - [Official Website](https://www.warp.dev/)
    ```sh
    brew install --cask warp
    ```

### Iterm settings:
- Hotkey: `Preferences -> Keys -> Hotkey`
- Native key mappings: `Preferences -> Profile -> Keys -> Key Mappings -> Presets... -> Native`

## Themes

- Powerlvl10k - [GitHub](https://github.com/romkatv/powerlevel10k)
    ```sh
    brew install romkatv/powerlevel10k/powerlevel10k
    echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
    ```

## CLI Tools

- tig - [GitHub](https://github.com/jonas/tig)
    ```sh
    brew install tig
    ```

- tldr - [Official Website](https://tldr.sh/)
    ```sh
    brew install tldr
    ```

- fzf - [GitHub](https://github.com/junegunn/fzf)
    ```sh
    brew install fzf
    $(brew --prefix)/opt/fzf/install
    ```

- Z - [GitHub](https://github.com/agkozak/zsh-z)
    ```sh
    git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z
    ```

- zsh-autosuggestions - [GitHub](https://github.com/zsh-users/zsh-autosuggestions)
    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```
- zsh-syntax-highlighting - [GitHub]()
  ```
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
    echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
  ```
  
- fx - [GitHub](https://github.com/antonmedv/fx)
    ```sh
    brew install fx
    ```

- Lvim - [Official Website](https://www.lunarvim.org/docs/installation)
    ```sh
    LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)
    ```

- bat - [GitHub](https://github.com/sharkdp/bat)
    ```sh
    brew install bat
    ```

- exa - [Official Website](https://the.exa.website/)
    ```sh
    brew install exa
    alias ls="exa"
    ```

## Applications

- Chrome
    ```sh
    brew install --cask google-chrome
    ```

- Jetbrains toolbox
    ```sh
    brew install --cask jetbrains-toolbox
    ```

- VSCode - [Official Website](https://code.visualstudio.com/)
    ```sh
    brew install --cask visual-studio-code
    ```

- Rectangle - [Official Website](https://rectangleapp.com/)
    ```sh
    brew install --cask rectangle
    ```

- Meetingbar - [GitHub](https://github.com/leits/MeetingBar)
    ```sh
    brew install --cask meetingbar
    ```

- Spotify - [Official Website](https://www.spotify.com/)
    ```sh
    brew install --cask spotify
    ```

- Maccy - Clipboard Manager [Official Website](https://maccy.app/)
    ```sh
    brew install --cask maccy
    ```

- Raycast - [Official Website](https://raycast.com/)
    ```sh
    brew install --cask raycast
    ```

- Cheatsheet - [Official Website](https://www.mediaatelier.com/CheatSheet/)
    ```sh
    brew install --cask cheatsheet
    ```
- Amphetamine - [Official App Store page](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12)

## Chrome Extensions

| Extension Name                 | URL                                                            |
|-------------------------------|----------------------------------------------------------------|
| Vimium                        | [Link](https://chrome.google.com/webstore/detail/dbepggeogbaibhgnhhndojpepiihcmeb) |
| Viewer Devtools               | [Link](https://chrome.google.com/webstore/detail/aahcojdfiikihlpfamimldmionifllkl) |
| Wix Insiders                  | [Link](https://chrome.google.com/webstore/detail/aofifmijnohoiikidmmhdohgjipaflak) |
| iWix Extension                | [Link](https://chrome.google.com/webstore/detail/ejfdniofoaeobdncklagejfcnfajnpgc) |
| Wix Statics Override          | [Link](https://chrome.google.com/webstore/detail/fhaehbcdbkccakpjgokgppjkggkmkmbl) |
| Wix Petri Sidekick            | [Link](https://chrome.google.com/webstore/detail/hpdjckcenihbjfmaccadiaighajcjope) |
| WIX BI Monitor                | [Link](https://chrome.google.com/webstore/detail/kpdeoodecbpgceddpmamibmgbbojjhjm) |
| Node.js V8 --inspector Manager (NiM) | [Link](https://chrome.google.com/webstore/detail/gnhhdgbaldcilmgcpfddgdbkhjohddkj) |
| Redux DevTools                | [Link](https://chrome.google.com/webstore/detail/lmhkpmbekcpmknklioeibfkpmmfibljd) |
| React Developer Tools         | [Link](https://chrome.google.com/webstore/detail/fmkadmapgofadopljbjfkapdkoienihi) |
| X-Seen-By                    | [Link](https://chrome.google.com/webstore/detail/fgbigkhiiddfchdehilplnapalobfjei) |
| Url Editor PRO                | [Link](https://chrome.google.com/webstore/detail/maoigfcibanjdgnepaiiadjhgmejclea) |
| Requestly                    | [Link](https://chrome.google.com/webstore/detail/mdnleldcmiljblolnjhpnblkcekpdkpa) |
| Proxy SwitchyOmega            | [Link](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif) |
| EditThisCookie                | [Link](https://chrome.google.com/webstore/detail/fngmhnnpilhplaeedifhccceomclgfbg) |
| JSON Viewer                   | [Link](https://chrome.google.com/webstore/detail/gbmdgpbipfallnflgajpaliibnhdgobh) |
| Better Pull Request for GitHub | [Link](https://chrome.google.com/webstore/detail/nfhdjopbhlggibjlimhdbogflgmbiahc) |
| Refined GitHub                | [Link](https://chrome.google.com/webstore/detail/hlepfoohegkhhmjieoechaddaejaokhf) |
| OctoLinker                    | [Link](https://chrome.google.com/webstore/detail/jlmafbaeoofdegohdhinkhilhclaklkp) |
| Web Vitals                    | [Link](https://chrome.google.com/webstore/detail/ahfhijdlegdabablpippeagghigmibma) |


## Chrome Search Engines

- Backoffice
    ```sh
    https://bo.wix.com/?q=%s
    ```

- Wix-life
    ```sh
    https://www.wix-life.com/search?q=%s
    ```

- GitHub wix-private
    ```sh
    https://github.com/search?q=%s+org%3Awix-private
    ```

## Git Aliases

```sh
 [alias]
     masterbase = !git fetch && git rebase origin/master && git push --force-with-lease
     lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
     co = checkout
     unstage = reset HEAD
     graph = log --all --graph --decorate --oneline
     undo = reset HEAD~1
     yarnshmock = "!f() { git checkout origin/master -- yarn.lock && yarn && git add yarn.lock && git commit -m 'Resolve yarn.lock conflict by accepting master branch version and running yarn' && git push;}; f"
