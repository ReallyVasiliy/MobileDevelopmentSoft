# Mobile Development Software Getting Started
Collection of software and scripts to aid in Android and iOS development. This repository is to help me get going in a new development environment.

## Essential software (OSX)

* [Homebrew](https://brew.sh/). To install: 
  
  `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* [Spectacle](https://www.spectacleapp.com/): Move and resize windows with keyboard shortcuts
  * CMD+OPT+F: Full screen
  * CMD+OPT+[arrow key]: Move window to corresponding half of screen
* [FlyCut](https://github.com/TermiT/Flycut): Clipboard manager
  * CMD+SHIFT+V: Pops up clipboard history. Use left/right arrow keys to navigate clipboard history
* [Sourcetree](https://www.sourcetreeapp.com/): GUI for git (useful for staging changes, browsing git log)
* [BBEdit](https://www.barebones.com/products/bbedit/): Text editor, with good regex support
  * Add to ~/.zshrc: `alias bb='open -a /Applications/BBEdit.app'`
* [XCode xip direct links](https://stackoverflow.com/a/10335943): Good SO answer listing all the releases in a clean way
* [iTerm2 + zsh + extensions](https://gist.github.com/kevin-smets/8568070)
  * `brew cask install iterm2`
  * Download [this theme](https://github.com/ReallyVasiliy/MobileDevelopmentSoft/blob/master/VasiliyTheme.itermcolors), or download themes from https://iterm2colorschemes.com/ 
  * `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
  * `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`
  * Then edit your `~/.zshrc` and add:
    * `ZSH_THEME="powerlevel9k/powerlevel9k"`
    * `POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(dir vcs)`
  * Install [Meslo font](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf)
  * Install [this other font](https://github.com/powerline/fonts/blob/master/SourceCodePro/Source%20Code%20Pro%20for%20Powerline.otf)
  * iTerm → preferences → profiles
    * Text → Change Font: select Meslo for Powerline
    * colors → color presets → import: select the theme you downloaded
    * colors → Turn on "Cursor guide" checkbox
    * window → Columns: 160 Rows: 50
  * Add syntax highlighting:
    * `brew install zsh-syntax-highlighting`
    * `source /usr/local/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh`
  * For more info go to https://gist.github.com/kevin-smets/8568070
  * Result:
  ![Screenshot of terminal](https://raw.githubusercontent.com/ReallyVasiliy/MobileDevelopmentSoft/master/terminal_screenshot.png)
  
  
## Configuration (OSX)
* `defaults write com.apple.finder AppleShowAllFiles YES`
