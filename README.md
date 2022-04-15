# NVIM

_My personal configuration to Nvim_

## Starting 🚀

- Cloning Project: 
```
git clone https://github.com/MartinMosqueira/nvim.git
```
- Remove file "plug.vim"
- Remove insider the "plugins" folder

### Pre-requisites 📋

- vim:```sudo apt-get install vim```
- [**nvim**](https://neovim.io/)

### Installation 🔧

- Install [**vim-plug**](https://github.com/junegunn/vim-plug):
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.config}"/nvim/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
- Install plugins
  ``` :PlugInstall```
- Install coc extension:
```
:CocInstall coc-json coc-tsserver coc-python coc-html-css-support coc-markdownlint
```

## Authors ✒️
* **Martin Mosqueira** - *Documentation* - [Martin Mosqueira](https://github.com/MartinMosqueira)

---
⌨️ con ❤️ por [Martin Mosqueira](https://github.com/MartinMosqueira) 😊
