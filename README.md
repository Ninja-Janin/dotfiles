My DOTFILES (~/.)
===

Why?
---
Because I noticed that copying my Custom VIM, GIT, BASH and TMUX configs to
work stations or servers took too much effort.

Notes
---
- will overwrite any custom VIM configs that you have!
- will overwrite any custom BASHRC configs that you have!
- will overwrite any custom TMUX configs that you have!
- requires: vim, curl, git, cmake, build-essential, python-dev, tmux, libclang-dev libboost-all-dev
- optional: zsh

Installation
---
```shell
# Install requirements START
## FOR Ubuntu/Debian
sudo apt-get install vim-gtk curl git cmake build-essential python-dev tmux -y

## FOR Mac
brew install vim-gtk curl git cmake build-essential python-dev tmux -y

## OR

## FOR Babun
pact install vim curl git cmake gcc-core gcc-g++ python tmux

# Install requirements END

## Make sure to run this in tmux

# seriously, that's it! and follow the prompts!
sh <(curl -sL https://raw.githubusercontent.com/mxaddict/dotfiles/master/install)

## FOR Mac
# seriously, that's it! and follow the prompts!
sh <(curl -sL https://raw.githubusercontent.com/mxaddict/dotfiles/mac/install)


## Install fonts
## git clone https://github.com/powerline/fonts (in Project directory)
## cd fonts
## ./install.sh

## in mac
## add Japanese keyboard and set font to Romanji to enable nerd tree


```

Platform support
---
I have only tested this on ubuntu and debian based systems.

Legacy Dotfiles
---
Looking for my old dotfiles? I moved them [here](https://github.com/mxaddict/dotfiles_legacy.git)

Docs
---
TODO: Make these...
