# ubuntu_library

## Install git
```sh
sudo apt-get install git
```
```sh
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"
```

## Install miniconda
```sh
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -o Miniconda3-latest-Linux-x86_64.sh
```
```sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
```
```sh
bash Miniconda3-latest-Linux-x86_64.sh
```

## Install zsh

```sh
sudo apt-get install curl
```
```sh
sudo apt-get install zsh -y
```
```sh
sudo curl -L http://install.ohmyz.sh | sh
```
```sh
zsh
```
```sh
sudo chsh -s $(which zsh)
```

## Install zsh auto-suggestion
```sh
cd ~/.oh-my-zsh/custom/plugins/
```
```sh
git clone git://github.com/zsh-users/zsh-autosuggestions
```
```sh
git clone git://github.com/zsh-users/zsh-syntax-highlighting
```
```sh
cd ../../../
```
```sh
nano .zshrc
```
Copy my .zshrc into .zshrc

## Install Docker
```sh
https://docs.docker.com/engine/install/ubuntu/
```
