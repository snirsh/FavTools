# FavTools
This repo has all my favorite and recommended tools for Mac

### Dev Tools

```sh
# xcode - https://mac.install.guide/commandlinetools/index.html
xcode-select --install

# brew - https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Terminal


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

### Themes

```sh
# powerlvl10k - https://github.com/romkatv/powerlevel10k
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

### CLI Tools
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

# fd - https://github.com/sharkdp/fd
brew install fd

# lvim - https://www.lunarvim.org/docs/installation
LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)

# bat - https://github.com/sharkdp/bat
brew install bat

# exa - https://the.exa.website/
brew install exa
alias ls="exa"
```

### Applications

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
```

### Chrome Extensions

```sh
aahcojdfiikihlpfamimldmionifllkl : Viewer devtools : version 2_0_4
ahfgeienlihckogmohjhadlkjgocpleb : Web Store : version 0_2
ahfhijdlegdabablpippeagghigmibma : Web Vitals : version 1_2_2
aofifmijnohoiikidmmhdohgjipaflak : Wix Insiders : version 0_0_61
dbepggeogbaibhgnhhndojpepiihcmeb : Vimium : version 1_67_4
ejfdniofoaeobdncklagejfcnfajnpgc : iWix Extension : version 1_10_28
fgbigkhiiddfchdehilplnapalobfjei : X-Seen-By : version 1_0_1
fhaehbcdbkccakpjgokgppjkggkmkmbl : Wix Statics Override : version 1_3_11
fmkadmapgofadopljbjfkapdkoienihi : React Developer Tools : version 4_27_8
fngmhnnpilhplaeedifhccceomclgfbg : EditThisCookie : version 1_6_3
gbmdgpbipfallnflgajpaliibnhdgobh : JSON Viewer : version 0_18_1
ghbmnnjooekpmoecnnnilnnbdlolhkhi : Google Docs Offline : version 1_62_0
gnhhdgbaldcilmgcpfddgdbkhjohddkj : Node.js V8 --inspector Manager (NiM) : version 2_8_1
hlepfoohegkhhmjieoechaddaejaokhf : Refined GitHub : version 23_6_2
hpdjckcenihbjfmaccadiaighajcjope : Wix Petri Sidekick : version 1_0_34
ipbomkmbokofodhhjpipflmdplipblbe : Advent of Code Charts : version 6_1_0
jgjaeacdkonaoafenlfkkkmbaopkbilf : ChatGPT for Google : version 3_0_4
jlmafbaeoofdegohdhinkhilhclaklkp : OctoLinker : version 6_10_5
kpdeoodecbpgceddpmamibmgbbojjhjm : WIX BI Monitor : version 1_1_0
lmhkpmbekcpmknklioeibfkpmmfibljd : Redux DevTools : version 3_0_19
maoigfcibanjdgnepaiiadjhgmejclea : Url Editor PRO : version 0_9_4_2
mdnleldcmiljblolnjhpnblkcekpdkpa : Requestly: Open Source HTTPs Debugging Proxy : version 23_5_19
mhjfbmdgcfjbbpaeojofohoefgiehjai : Chrome PDF Viewer : version 1
neajdppkdcdipfabeoofebfddakdcjhd : Google Network Speech : version 1_0
nfhdjopbhlggibjlimhdbogflgmbiahc : Better Pull Request for GitHub : version 1_0_37
nkeimhogjdpnpccoofpliimaahmaaome : Google Hangouts : version 1_3_21
nmmhkkegccagdldgiimedpiccmgmieda : Chrome Web Store Payments : version 1_0_0_6
padekgcemlokbadohgkifijomclgjgif : Proxy SwitchyOmega : version 2_5_21
```
