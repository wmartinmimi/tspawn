# tspawn

Simple script to spawn extra shells in termux.

This script can bypass the 8 shell limit.

It works by calling the activity manager.

## How To Use

### Installation

```bash
apt install wget
cd $PREFIX/bin
wget https://raw.githubusercontent.com/wmartinmimi/tspawn/main/tspawn
chmod 700 tspawn
```

### Usage

Enter the following command to spawn new shells:

```bash
tspawn
```

### Uninstallation

```bash
cd $PREFIX/bin
rm tspawn
```
