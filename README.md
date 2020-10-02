# windows_like_a_mac
my braindump do convert my windows machine into something mac like

upgrade to 1909 ????

install wsl
```powershell

```


install laspass from source:
```bash
sudo apt-get --no-install-recommends -yqq install \
  bash-completion \
  build-essential \
  cmake \
  libcurl4  \
  libcurl4-openssl-dev  \
  libssl-dev  \
  libxml2 \
  libxml2-dev  \
  libssl1.1 \
  pkg-config \
  ca-certificates \
  xclip
  
git clone https://github.com/lastpass/lastpass-cli
cd lastpass-cli
make
sudo make install
```
```bash

```

install cascadia code fonts [cascadia](https://github.com/microsoft/cascadia-code/releases)

run ubuntu

```bash
sudo apt install zsh -y
bash "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/agnoster/agnoster-zsh-theme.git ~/.oh-my-zsh/custom/themes/agnoster
```

```
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```
s
