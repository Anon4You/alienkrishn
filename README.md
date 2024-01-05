![logo](Images/Picsart_23-12-16_00-22-42-640.jpg)

# alienkrishn
A custom termux apt repository maintained by me 


## add Repo
```
apt install gnupg -y
mkdir -p $PREFIX/etc/apt/sources.list.d
echo "deb [arch=all] https://anon4you.github.io/alienkrishn anon main" > $PREFIX/etc/apt/sources.list.d/alienkrishn.list
curl -sSL https://github.com/Anon4You/alienkrishn/raw/main/alienkrishn.key | apt-key add
mv $PREFIX/etc/apt/trusted.gpg $PREFIX/etc/apt/trusted.gpg.d
apt update 
```
## Available Packages
* androdos
* androvirus
* apktool
* cctvip
* enctool
* iginfobot
* instainfo
* kalilinux
* locateme
* powerdos
* shorturl
* sqlmap
* termux-desktop
* webinfo
* wserver
* zphisher

## Usage
type alinekrishn in termux to show usage information

## Author
* [Alienkrishn](https://www.instagram.com/alienkrishn) / [Anon4You](https://github.com/Anon4You)
