### UPGRADE FOR DEBIAN
```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

###  UPGRADE FOR UBUNTU
```
apt update && apt upgrade -y && update-grub && sleep 2 && reboot
```

### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://vip.nixystore.my.id/nixy.sh && chmod +x nixy.sh && ./nixy.sh
```

### UPDATE SCRIPT
```
wget -q https://vip.nixystore.my.id/nixystore.sh && chmod +x nixystore.sh && ./nixystore.sh
