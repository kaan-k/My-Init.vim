# My-Init.vim
## Installation

My init.vim requires [Node.js](https://nodejs.org/) v10+ to run.

 - Install node from AUR and compile it.

```sh
git clone https://aur.archlinux.org/nodejs-git.git
```
```sh
cd nodejs-git
```
```sh
makepkg -si
```

Install Vim-Plug

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Install the coc extensions and you are good to go.


## License

What Lisence, LOL!

**Free Software, Hell Yeah!**