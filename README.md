# My-Init.vim
## Installing Dependencies

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
- Install npm
```sh
sudo pacman -S npm
```
- Install Mono
```sh
sudo pacman -S mono
```
- After installing mono, you might have to copy paste this line to your terminal.
```sh
export FrameworkPathOverride=/usr/lib/mono/4.5/
```
- Install .NET
```sh
sudo pacman -S dotnet-runtime
```

- Install Vim-Plug

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Install the coc extensions and you are good to go.


## License

Nothing to see here.

