## firefox  
  
A popular open source graphical web browser  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/firefox/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install firefox
```  

Fedora Based:

```shell
yum install firefox
```  

Arch Based:

```shell
pacman -S firefox
```  

MacOS:  

```shell
brew install firefox
```
  
```shell
mv -fv "$HOME/.config/firefox" "$HOME/.config/firefox.bak"
mv -fv "$HOME/.mozilla" "$HOME/.mozilla.bak"
git clone https://github.com/dfmgr/firefox "$HOME/.config/firefox"
mkdir -p "$HOME/.mozilla"; ln -sf "$APPDIR" "$HOME/.mozilla/firefox"

```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/firefox" target="_blank" rel="noopener noreferrer">firefox wiki</a>  |  
  <a href="https://www.mozilla.org/firefox" target="_blank" rel="noopener noreferrer">firefox site</a>
</p>  
