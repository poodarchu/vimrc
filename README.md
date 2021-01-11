# vimrc based on NeoVim

## Get Started

### 1. Install NeoVim

AppImage ("universal" Linux package)
The Releases page provides an AppImage that runs on most Linux systems. No installation is needed, just download nvim.appimage and run it. (It might not work if your Linux distribution is more than 4 years old.)
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage
```
If the ./nvim.appimage command fails, try:

```
./nvim.appimage --appimage-extract
./squashfs-root/AppRun --version
```

# Optional: exposing nvim globally
```
mv squashfs-root / && ln -s /squashfs-root/AppRun /usr/bin/nvim
nvim
```

### 2. add init.vim to ~/.config/nvim/

### 3. get into the editor and execute ```PlugInstall```
