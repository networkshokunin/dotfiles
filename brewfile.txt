# 'brew tap'
tap "romkatv/powerlevel10k"
tap "homebrew/autoupdate"

#brew installs
brew "go"
brew "git"
brew "powerlevel10k"
brew "zsh-syntax-highlighting"
brew "zsh-autosuggestions"
brew "gnupg"
brew "pinentry-mac"
brew "pyenv"
brew "autojump"
brew "fzf"

# set arguments for all 'brew install --cask' commands
cask_args appdir: "/Applications"

cask "setapp", greedy:true
cask "rectangle", greedy: true
cask "appcleaner", greedy: true
cask "visual-studio-code", greedy: true
cask "alfred", greedy: true
cask "kitty", greedy: true
cask "signal", greedy: true
cask "shottr", greedy: true
cask "brooklyn", greedy: true
cask "whatsapp", greedy:true
cask "1Password", greedy:true
cask "google-drive", greedy:true
cask "obsidian", greedy:true
