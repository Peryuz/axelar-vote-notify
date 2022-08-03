# axelar-vote-notify
Axelar voter notify bot. 

## Setup

```bash
cd $HOME
mkdir $HOME/voter && cd $HOME/voter
wget https://raw.githubusercontent.com/Errorist79/axelar-vote-notify/main/app.py
sudo apt-get install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.8
sudo apt-get install python3-pip -y
python3 -m pip install os-sys
python3 -m pip install requests
python3 -m pip install -U discord.py
```

Start 

```bash
python3 app.py
```
