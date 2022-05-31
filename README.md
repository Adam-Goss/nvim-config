# nvim-config
My Neovim config

IMPORTANT Requires [Neovim v0.8.0]]

Install neovim with:
- `sudo pacman -S neovim`
- `sudo apt install neovim`

Clone repo and copy to .config directory with:
- `mkdir ~/.config/nvim`
- `git clone https://github.com/Adam-Goss/nvim-config.git && cp -r nvim-config/* ~/.config/nvim/.`


Install Neovim python support with:
- `pip install pynvim`

Install Neovim node support with:
- `npm i -g neovim`

Run `nvim` and wait for the plugins to be installed

NOTE (You will notice treesitter pulling in a bunch of parsers the next time you open Neovim)

Check health in neovim with:
- `:checkhealth`

Sync plugins with:
- `:PackerSync`
