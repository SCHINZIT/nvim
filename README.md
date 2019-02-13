# Better use
this link [git.schinz.it](https://git.schinz.it/dotfiles/nvim)  

# Neovim config dir

# HoWto Enable

To use this configuration you have to ln to the correct init.vim.  
Since I'm using some different environments and styles, I'm keeping diffent configs for vim in different locations. Linking init.vim to these configs makes it easy to switch between configurations.  

The script `switch-nvim-config` helps linking the configuration.  
Calling `switch-nvim-config` without arguments just enables this config-set.  
Calling with an <argument> would enable a config in `~./config/<argument>`.  
If you want you can put the script in your $PATH.  

## Prequesites

### Javascript

**deoplete** && **ternjs**  

Python must be enabled. So install with pip2 / pip3.  

`pip2 install neovim`  
`pip3 install neovim`  

Node.js and npm must be installed in order to run ternjs.  

### Elm

**elmcast/elm-vim**  

To use the plugin with most features you have to install the elm... stack.  

`sudo npm install -g elm elm-test elm-oracle`  

## Install Addons/Plugins

Start neovim and call `:PlugInstall`.  

