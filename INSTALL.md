# Alienkrishn

## Instalation

> Just copy and paste all commands<br>in your termux

```
apt install gnupg -y
```
```
curl -sSL https://raw.githubusercontent.com/Anon4You/alienkrishn/main/alienkrishn.key | apt-key add 
```
```
mv $PREFIX/etc/apt/trusted.gpg $PREFIX/etc/apt/trusted.gpg.d
```
```
mkdir -p $PREFIX/etc/apt/source.list.d
```

```
echo "deb [arch=all] https://Anon4You.github.io/alienkrishn anon main" > $PREFIX/etc/apt/source.list.d/alienkrishn.list
```
```
apt update
```

