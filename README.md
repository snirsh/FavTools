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

- brew - The missing package manager for macOS (or Linux), used to install, update and uninstall software. [Official Website](https://brew.sh/)
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

## Terminal

- iterm2 - An open-source replacement for Apple's Terminal. It's highly customizable and comes with a lot of useful features. [Official Website](https://iterm2.com)
    ```sh
    brew install --cask iterm2
    ```

- zsh - An extended Bourne shell with a large number of improvements, including some features of Bash, ksh, and tcsh. [Official Website](https://www.zsh.org/)
    ```sh
    brew install zsh
    ```

- Oh-my-zsh - A community-driven and open-source framework for managing your ZSH configuration. It comes with a lot of helpful functions, helpers, plugins, and themes. [Official Website](https://ohmyz.sh/)
    ```sh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    ```

- Warp - A blazingly fast, intuitive terminal specifically designed for developers. [Official Website](https://www.warp.dev/)
    ```sh
    brew install --cask warp
    ```

### Iterm settings:
- Hotkey: `Preferences -> Keys -> Hotkey`
- Native key mappings: `Preferences -> Profile -> Keys -> Key Mappings -> Presets... -> Native`

## Themes

- Powerlvl10k - A theme for Zsh. It emphasizes speed, flexibility, and out-of-the-box experience. [GitHub](https://github.com/romkatv/powerlevel10k)
    ```sh
    brew install romkatv/powerlevel10k/powerlevel10k
    echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
    ```

## CLI Tools

- tig - Text-mode interface for git. Tig is a git repository browser that additionally can act as a pager for output from various git commands. [GitHub](https://github.com/jonas/tig)
    ```sh
    brew install tig
    ```

- tldr - A collection of simplified and community-driven man pages. [Official Website](https://tldr.sh/)
    ```sh
    brew install tldr
    ```

- fzf - A general-purpose command-line fuzzy finder. It's an interactive Unix filter for command-line that can be used with any list. [GitHub](https://github.com/junegunn/fzf)
    ```sh
    brew install fzf
    $(brew --prefix)/opt/fzf/install
    ```

- Z - Jump around. Tracks your most used directories, based on 'frecency'. [GitHub](https://github.com/agkozak/zsh-z)
    ```sh
    git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z
    ```

- zsh-autosuggestions - Fish-like fast/unobtrusive autosuggestions for zsh. It suggests commands as you type, based on command history. [GitHub](https://github.com/zsh-users/zsh-autosuggestions)
    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

- zsh-syntax-highlighting - Provides syntax highlighting for the shell zsh. It enables highlighting of commands whilst they are typed at a zsh prompt into an interactive terminal. [GitHub](https://github.com/zsh-users/zsh-syntax-highlighting)
    ```sh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
    echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
    ```

- fx - Command-line JSON processing tool. [GitHub](https://github.com/antonmedv/fx)
    ```sh
    brew install fx
    ```

- Lvim - LunarVim is a distribution of neovim crafted to ensure you are working in a moon-like development environment. [Official Website](https://www.lunarvim.org/docs/installation)
    ```sh
    LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)
    ```

- bat - A cat clone with syntax highlighting and git integration. [GitHub](https://github.com/sharkdp/bat)
    ```sh
    brew install bat
    ```

- exa - A modern replacement for 'ls'. Exa is a modern replacement for the command-line program ls that ships with Unix and Linux operating systems, with more features and better defaults. [Official Website](https://the.exa.website/)
    ```sh
    brew install exa
    alias ls="exa"
    ```

## Applications

- Chrome
    ```sh
    brew install --cask google-chrome
    ```

- Jetbrains toolbox - Helps to manage and keep JetBrains IDEs up to date. Provides a simple and convenient way to keep track of all your IDE projects and applications. 
    ```sh
    brew install --cask jetbrains-toolbox
    ```

- VSCode - A freeware source-code editor made by Microsoft for Windows, Linux and macOS. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. [Official Website](https://code.visualstudio.com/)
    ```sh
    brew install --cask visual-studio-code
    ```

- Rectangle - A window management application for MacOS. It allows the user to quickly and easily manage their windows, without the need for complex and time consuming dragging. [Official Website](https://rectangleapp.com/)
    ```sh
    brew install --cask rectangle
    ```

- Meetingbar - A macOS menu bar app for your calendar meetings (Google, Outlook, Zoom, MS Teams, Webex, Jitsi, RingCentral, Hangouts, Telephone, Lark, etc). Quickly join meetings from event or create ad hoc meeting. [GitHub](https://github.com/leits/MeetingBar)
    ```sh
    brew install --cask meetingbar
    ```

- Spotify - [Official Website](https://www.spotify.com/)
    ```sh
    brew install --cask spotify
    ```

- Maccy - A lightweight clipboard manager for macOS. It keeps your copy history at hand, so you don't have to worry about losing any copied data. [Official Website](https://maccy.app/)
    ```sh
    brew install --cask maccy
    ```

- Raycast - The macOS command line bar. It lets you control your tools with a few keystrokes and create your own script commands. [Official Website](https://raycast.com/)
    ```sh
    brew install --cask raycast
    ```

- Cheatsheet - A simple tool for macOS that gives you access to shortcuts of the application you are using, just by holding the command key. [Official Website](https://www.mediaatelier.com/CheatSheet/)
    ```sh
    brew install --cask cheatsheet
    ```

- Amphetamine - An app for macOS that keeps your machine awake for a configurable amount of time. Perfect for when you're reading, working, or doing a presentation. [Official App Store page](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12)


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
You can use my official [Annie-Bunny](https://github.com/snirsh-wix/annie-bunny)

Or make your own! in [chrome://settings/searchEngines](Chrome Settings)
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
