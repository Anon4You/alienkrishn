# Alienkrishn Repo
![logo](Picsart_23-12-16_00-22-42-640.jpg)
## Instalation
```
apt install gnupg -y
```
```
mkdir -p $PREFIX/etc/apt/sources.list.d
```
```
echo "deb [arch=all] https://anon4you.github.io/alienkrishn anon main" > $PREFIX/etc/apt/sources.list.d/alienkrishn.list
```
```
curl -sSL https://github.com/Anon4You/alienkrishn/raw/main/alienkrishn.key | apt-key add
```
```
mv $PREFIX/etc/apt/trusted.gpg $PREFIX/etc/apt/trusted.gpg.d
```
```
apt update
```
## Usage
```
apt install alienkrishn -y && alienkrishn
```

