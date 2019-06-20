# Overview
Script to install Aporeto apoctl, enforcerd and useful utilities

## Example
Download script
```
curl -L -o install https://tinyurl.com/yxmv25rz
chmod +x install
```
Install enforcerd
```
export ENFORCERD_NAMESPACE=/jody/abc
sudo ./install enforcerd
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
export ENFORCERD_NAMESPACE=/jody/abc
sudo ./install all
```

## Quick
Requires that ENFORCERD_NAMESPACE is set and you are root
```
curl -L -o install https://tinyurl.com/yxmv25rz | bash all
```
