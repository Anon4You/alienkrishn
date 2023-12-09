# alienkrishn
A custom termux apt repository maintained by me 


## add key 

```
apt install gnupg -y && curl -sSL https://github.com/Anon4You/alienkrishn/raw/main/alienkrishn.key | apt-key add
```

## add source list

```
echo "deb [trusted=yes arch=all] https://anon4you.github.io/alienkrishn anon main" > $PREFIX/etc/apt/sources.list.d/alienkrishn.list
```

## Author
* [Alienkrishn](https://www.instagram.com/alienkrishn) / [Anon4You](https://github.com/Anon4You)
