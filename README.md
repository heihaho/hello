# vimSettings
The vim setting inspired from amix

## Core Feature
* A light vimrc with only 7mb in size
* Change the plugin architechure from amix's pathogen to newest native vim8 plug
* Simplify the file structure to 1 vimrc
* Use native feature if it is provided
* eliminate key binding for you to customize yourself

## How to install

### For windows
Download vim with this link: https://ftp.nluug.nl/pub/vim/pc/gvim81.exe <br>
Download git with this link: https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe
<br>Then open git bash
```
git clone https://github.com/heihaho/vimSettings.git
cd vimSettings
mv .vim $HOME\vimfiles
mv .vimrc $HOME/.vimrc
```
### For mac
```
brew install git 
git clone https://github.com/heihaho/vimSettings.git
cd vimSettings
mv .vimrc ~/.vimrc
mv .vim ~/.vim
```

### For Linux(Ubuntu)

```
sudo apt-get git
sudo apt-get vim
git clone https://github.com/heihaho/vimSettings.git
cd vimSettings
mv .vimrc ~/.vimrc
mv .vim ~/.vim
```

### For Linux (Arch)

```
pacman -Sy git
pacman -Sy vim
git clone https://github.com/heihaho/vimSettings.git
cd vimSettings
mv .vimrc ~/.vimrc
mv .vim ~/.vim
```

### For Linux (Fedora)

```
rpm -i git
rpm -i vim
git clone https://github.com/heihaho/vimSettings.git
cd vimSettings
mv .vimrc ~/.vimrc
mv .vim ~/.vim
```
