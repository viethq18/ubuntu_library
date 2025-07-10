# ubuntu_library

## Install huggingface download model
```sh
pip install "huggingface_hub[hf_transfer]"
HF_HUB_ENABLE_HF_TRANSFER=1 huggingface-cli download deepseek-ai/deepseek-vl2-small --local-dir ./deepseek-vl2-small
```

## Install git lfs
```sh
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
```

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

## Create new user
```sh
sudo -i
adduser viethq5
usermod -aG sudo viethq5
su - viethq5
sudo ls
sudo usermod -aG docker $USER

