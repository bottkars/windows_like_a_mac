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


install cascadia code fonts [cascadia](https://github.com/microsoft/cascadia-code/releases)

run ubuntu

```bash
sudo apt install zsh unzip -y
eval "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/agnoster/agnoster-zsh-theme.git ~/.oh-my-zsh/custom/themes/agnoster
```

```python
pip install 'ansible[AZURE]'
```
create rsa key
```bash
ssh-keygen -t rsa -b 4096
```


install the cloud cli´s
```bash
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64-2.0.30.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```
```bash
sudo wget -q -O - https://raw.githubusercontent.com/starkandwayne/homebrew-cf/master/public.key | sudo  apt-key add -
sudo echo "deb http://apt.starkandwayne.com stable main" | sudo  tee /etc/apt/sources.list.d/starkandwayne.list
sudo apt-get update
sudo apt-get install om bosh-cli yq jq cf7-cli -y
```

