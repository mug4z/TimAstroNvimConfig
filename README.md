# AstroNvim Template

**NOTE:** This is for AstroNvim v5+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Clone the repository

```shell
git clone https://github.com/mug4z/TimAstroNvimConfig "${XDG_CONFIG_HOME:-$HOME/.config}"/astro
```

#### Start Neovim
Add an alias to use the config, now use astro to open nvim with astro config
```shell
cat >> $HOME/.bashrc << EOF
alias astro='NVIM_APPNAME="astro" nvim'
EOF
source $HOME/.bashrc
```
```shell
astro
```
