# Linux Notes

## Update
```
sudo apt-get update
sudo apt-get dist-upgrade
```

## Install git
```
sudo apt-get install git
```

## Install Atom, check latest version!!!
```
wget https://github.com/atom/atom/releases/download/v1.8.0/atom-amd64.deb
sudo dpkg --install atom-amd64.deb
```

## Additional software
```
# GIMP
sudo apt-get install gimp

# Chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i --force-depends google-chrome-stable_current_amd64.deb

```

## VS
```
1. Download with browser
2. sudo dpkg --install vscode-amd64.deb
```

## .NET Core

http://dot.net

sudo sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet/ xenial main" > /etc/apt/sources.list.d/dotnetdev.list'




## Shell
```
#!/bin/bash

chmod +x myscript
```

