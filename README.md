## 👋 Welcome to kitty 🚀  

 Install configurations for kitty  
  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

OR

### Automatic install/update  

```shell
dfmgr update kitty
```
  
### requirements  
  
#### Debian based

```shell
apt install kitty
```  

#### Fedora Based

```shell
yum install kitty
```  

#### Arch Based

```shell
pacman -S kitty
```  

#### MacOS  

```shell
brew install kitty
```
  
#### Manual install  

```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/kitty"
mv -fv "$HOME/.config/kitty" "$HOME/.config/kitty.bak"
git clone https://github.com/dfmgr/kitty "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/kitty/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```

## Author  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ dfmgr: [Github](https://github.com/dfmgr) ⛵  

## Links

<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/kitty" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/kitty.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/kitty" target="_blank" rel="noopener noreferrer">kitty wiki</a>  |  
  <a href="kitty" target="_blank" rel="noopener noreferrer">kitty site</a>
</p>  
