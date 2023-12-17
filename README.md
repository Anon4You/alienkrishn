![logo](Images/Picsart_23-12-16_00-22-42-640.jpg)

# alienkrishn
A custom termux apt repository maintained by me 


## add key 

```
curl -sSL https://github.com/Anon4You/alienkrishn/raw/main/alienkrishn.key | apt-key add && mv $PREFIX/etc/apt/trusted.gpg $PREFIX/etc/apt/trusted.gpg.d 
```

## add source list

```
echo "deb [trusted=yes arch=all] https://anon4you.github.io/alienkrishn anon main" > $PREFIX/etc/apt/sources.list.d/alienkrishn.list
```
## Available Packages
* androvirus
* apktool
* cctvip
* enctool
* iginfobot
* instainfo
* kalilinux
* sqlmap
* termux-desktop
* webinfo
* wserver
* zphisher
## Usage 
> apt install {package_name}

## Author
* [Alienkrishn](https://www.instagram.com/alienkrishn) / [Anon4You](https://github.com/Anon4You)
