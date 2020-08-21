## firefox  
  
a popular open source graphical web browser  
  
requires:    
```
apt install firefox
```  
```
yum install firefox
```  
```
pacman -S firefox
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/firefox/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/firefox" "$HOME/.config/firefox.bak"
git clone https://github.com/dfmgr/firefox "$HOME/.config/firefox"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/firefox" target="_blank">firefox wiki</a>  |  
  <a href="https://www.mozilla.org/firefox" target="_blank">firefox site</a>
</p>  
