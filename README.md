# DevJ's Neovim Configuration
Based on Kickstart.nvim

## Installation (Debian)
```sh

sudo apt install make gcc ripgrep unzip git xclip curl
sudo apt install python3-venv node php

# Now we install nvim
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
sudo rm -rf /opt/nvim-linux-x86_64
sudo mkdir -p /opt/nvim-linux-x86_64
sudo chmod a+rX /opt/nvim-linux-x86_64
sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz

# make it available in /usr/local/bin, distro installs to /usr/bin
sudo ln -sf /opt/nvim-linux-x86_64/bin/nvim /usr/local/bin/

git clone git@github.com:DeveloperJose/nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
