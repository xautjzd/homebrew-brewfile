# 'brew tap'
tap "homebrew/cask"
tap "homebrew/core"

# set arguments for all 'brew install --cask' commands
cask_args appdir: "/Applications", require_sha: true

# brew install
brew "git"
brew "zsh"
brew "neovim"
brew "emacs"
brew "docker"
brew "maven"
brew "rust-analyzer"
brew "node"
brew "tmux"
brew "bat"
brew "ripgrep"
brew "fd"
brew "coreutils"
brew "fzf"
brew "curl"
brew "wget"
brew "telnet"
brew "jq"
brew "tree"

# brew install --cask
cask 'alfred'
cask "google-chrome"
cask "firefox"

cask 'iterm2'
cask 'dash'
cask "visual-studio-code"
cask "sequel-pro"
cask "java" unless system "/usr/libexec/java_home --failfast"
cask "intellij-idea-ce"
cask "tunnelblick"
cask "wireshark"

cask "telegram"
cask "clashx"
