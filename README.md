# Overview

Personal neovim configuration. Current setup is for neovim 0.9.5. Minor plugin issues when using neovim 0.10.0 and onwards have been found.

Don't forget additional utilities are needed for certain plugins. Common one I've found missing on distros is ```ripgrep```.

```sudo apt install vim```

```
curl -LO https://github.com/neovim/neovim/releases/download/v0.9.5/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
```

Add to ~/.bashrc
```
export PATH="$PATH:/opt/nvim-linux64/bin"
alias vim="nvim"
```
