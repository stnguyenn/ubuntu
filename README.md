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
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

## python
```
sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.9
```

## go
```
sudo add-apt-repository ppa:longsleep/golang-backports
sudo apt update
sudo apt install golang-go
```

## node
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install nodejs
```
