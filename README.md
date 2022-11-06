## Directory Structure
---
#### `lain`
- One of the libraries used in the theme
#### `freedesktop`
- A library used in the theme
#### `themes` 
- Folder containing all the themes

## Issue Tracking
---
- TODO: Consoldate all library folders into one place
- TODO: Rebrand, chaning name
- TODO: Support multiple monitor backgrounds with auto-detection
- TODO: Add SSID indetification in taskbar

## Apt Packages
- `sudo apt-get install awesome`
- `sudo apt-get install zsh`
- `sudo apt-get install lutris`
- `sudo apt-get install neovim`
- `sudo apt-get install steam`
- `sudo apt-get install nodejs`
- `sudo apt-get install xcompmgr`
- `sudo apt-get install neofetch`

## `snap` Packages
- `snap install spotify`

## Downloaded `.deb` Packages
- `discord`

## Configuration Settings
- `chsh -s $(which zsh)` - Set `zsh` as default terminal
- `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` - Install oh-my-zsh
- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k` - Install powerlevel 10k
- Install proper font
  - `https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf`
  - `https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf`
  - `https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf`
  - `https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf`
  - Double-click on font file
- Configure `konsole` to use font
- Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`
---
- Add lines to `.zshrc`
```
HISTSIZE = 30000
HISTFILESIZE = 40000
```
---
- Add `~/.config/nvim/init.vim` after neovim install
- Run `:PlugInstall` in `nvim` 
---
- Download and install [vmware player](https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-player/workstation-player-evaluation.html.html)
