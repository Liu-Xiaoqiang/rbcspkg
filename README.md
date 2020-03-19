# Warning ! ! !
This repository will not be updated in future, please use another one on [Chipsee](https://github.com/Chipsee/rbcspkg)

# Introduction
We will use this repo to contain the source code and config for Chipsee Raspberry Computer Module Hardware.

# How to use
## Prepare system
You can install raspberry pi official system, please reference [raspbian.](https://www.raspberrypi.org/downloads/raspbian/)
## Download rbcspkg
```
git clone --depth=1 --branch `uname -r` https://github.com/Chipsee/rbcspkg.git
```
## Compile and install
```
cd rbcspkg
sudo make install
```
## Uninstall
```
cd rbcspkg
sudo make uninstall
```
## More commands
```
cd rbcspkg
make help
```
