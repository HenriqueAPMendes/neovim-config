# kickstart.nvim

## Introduction

My personal configs for neovim

## Installation

<details><summary>Ubuntu Install Steps</summary>

```sh
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git neovim
git clone https://github.com/HenriqueAPMendes/neovim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

</details>

### Post Installation

Start Neovim

```sh
nvim
```

Lazy will automatically install all the plugins.
