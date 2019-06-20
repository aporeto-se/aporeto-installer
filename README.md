# Overview
Script to install Aporeto apoctl, enforcerd and useful utilities

## Example
Download script
```
curl -L -o install https://tinyurl.com/y2f94eja && chmod +x install
```
Install enforcerd
```
export ENFORCERD_NAMESPACE=/jody/abc && sudo ./install enforcerd
```
Install apoctl
```
sudo ./install apoctl
```
Install tools
```
sudo ./install tools
```
Install ALL
```
export ENFORCERD_NAMESPACE=/jody/abc && sudo ./install all
```
Quick
```
curl -L -o install https://tinyurl.com/y2f94eja && chmod +x install
export ENFORCERD_NAMESPACE=/jody/abc && sudo ./install all
```
