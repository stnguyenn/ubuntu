# ubuntu
setup-scripts

## sudoer
```
sudo visudo
# %sudo   ALL=(ALL:ALL) NOPASSWD:ALL

```

## essential
```
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install -y \
    build-essential \
    vim \
    chromium-browser \
    curl \
    libssl-dev \
    git
sudo apt-get install -y zsh
curl -L http://install.ohmyz.sh | sh

```
