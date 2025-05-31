INSTALL SCRIPT
1. :
```
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub
```
2. :
```
apt install curl jq wget screen build-essential -y && reboot
```
3. :
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/frosi4524/coklat/refs/heads/main/install.sh && chmod +x install.sh && ./install.sh
```
ANTERNATIF
```
apt-get update -y && apt install curl wget bzip2 gzip xz-utils screen && if [[ ! -d /etc/xdtmp ]]; then mkdir -p /etc/xdtmp; fi && wget -q https://raw.githubusercontent.com/rosicenter691/sc-vip/main/install.sh && chmod +x install.sh && screen -S install ./install.sh
```
