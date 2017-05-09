# motd

Display motd on debian and show system info

## Requirements

```
apt install lsb-release
```

## Installation

```
git clone https://github.com/rda0/motd.git
cd motd
echo '' > /etc/motd
rm /etc/update-motd.d/10-uname
cp motd /etc/update-motd.d/10-motd
```
