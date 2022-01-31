### Install by PIP (Recommended)

Before continuing make sure following requirements are satisfied:

- Python version greater than or equal to 3.4 is installed
- pip is installed for Python 3

Install `blast` package by running:

```shell script
pip3 install blast
```

Run TBomb by just typing:
```shell script
blast
```

### Install from GIT


>Running `blast.sh` as sudo miscofigures files ownership. It is recommended not to run it as sudo

Run these commands to clone and run blast.

#### For Termux

To use the bomber type the following commands in Termux:
```shell script
pkg install git -y 
pkg install python -y 
git clone https://github.com/yogeshpcte/blast.git
cd blast
bash blast.sh
```

#### For iSH

To use the application, type in the following commands in iSH.
```shell script
apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/yogeshpcte/blast.git
cd blast
pip3 install -r requirements.txt
chmod +x blast.sh
bash blast.sh
```

#### For Debian-based GNU/Linux distributions

To use the application, type in the following commands in GNU/Linux terminal.
```shell script
sudo apt install git
git clone  https://github.com/yogeshpcte/blast.git
cd blast
bash blast.sh
```





##### Install dependencies:

```shell script
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/yogeshpcte/blast.git
cd blast
bash blast.sh
```

