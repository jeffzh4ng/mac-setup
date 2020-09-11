# mac-setup
Personal setup instructions for new machines

## System Settings
- Software update
- Display
    - Scaled resolution
    - General > turn off font smoothing
- Trackpad
    - Fast tracking speed, tap to click, three finger gesture
- Accessibility zoom
- Dock
    - Remove all apps
    - Place dock on left
    - Turn hiding on
- Finder
    - Show path bar (View > Show Path Bar)
    - Show status bar (View > Show Status Bar)
    - Show scroll bar (System preferences > General > Show Scroll Bars: Always)
    - Show hidden files
    - Customize panel
- Misc
    - Show battery percentage
    - Keyboard speed
- Screenshot
    - Remove floating window (CMD + Shift + 5)
    - Remove drop shadow
        - defaults write com.apple.screencapture disable-shadow -bool true ; killall SystemUIServer

## Applications
- Xcode, xcode-select --install
- Home-brew
    - /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    - brew update
- brew cask install iterm2
- Zsh, oh-my-zsh
    - Autojump
    - Syntax-highlighting
- SF Mono Font for Powerline
- brew install git
- brew cask install google-chrome
- brew cask install alfred
- brew cask install spotify
- brew cask install flux
    - Set CMD + space to launch alfred
- brew cask install vscode 
    - sync settings
- brew install nvm
    - nvm install stable
- brew install yarn
- brew install postgres
    - brew services start postgresql
- yarn global add typescript
- yarn global add trash-cli
- curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh


Docker
Flux
Stretchly
Zoom

# Load zsh-syntax-highlighting; should be last.	
	source /usr/share/zsh/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh 2>/dev/null
# Load zsh-syntax-highlighting; should be last.	
	source /usr/share/zsh/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh 2>/dev/null
