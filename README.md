# UbuntuSetup


```
sudo apt update &&\
sudo apt install zsh &&\
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" &&\

sed 's/robbyrussell/agnoster/g' ~/.zshrc

sudo git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
sudo git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

sed 's/robbyrussell/agnoster/g' ~/.zshrc
sed 's/plugins=(git/plugins=(git sudo zsh-syntax-highlighting zsh-autosuggestions/g' ~/.zshrc

git  clone https://github.com/abertsch/Menlo-for-Powerline.git 
sudo mv Menlo*.tff /usr/share/fonts


```


```
sudo snap install --classic code # or code-insiders
```

```
sudo apt install nodejs
npm install -g typescript


curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

curl https://nim-lang.org/choosenim/init.sh -sSf | sh
```

```
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb

sudo apt-get update; \
  sudo apt-get install -y apt-transport-https && \
  sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-5.0
```



