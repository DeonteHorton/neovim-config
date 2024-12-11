# AstroNvim Template

**NOTE:** This is for AstroNvim v4+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```

### Notes

> To utlize some of the LSPs ( Language Server Protocol ) for linting, formatting, and etc. Please be sure to install the language(s) on your local machine.
>
> To install extra plugins, visit [https://github.com/AstroNvim/astrocommunity](https://github.com/AstroNvim/astrocommunity) and add them to the `lua/community.lua` file.
>
> Formatter is turned off. To turn on, go to the `lua/plugins/astrolsp.lua` file. Formatting variable is on line 18
>
> ## Bonus tools to install via command line
>
> - [lazygit](https://github.com/jesseduffield/lazygit)
> - [fzf](https://github.com/junegunn/fzf)

  
