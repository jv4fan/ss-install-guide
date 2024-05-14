# ss-install-guide
## for linux ubuntu
### change version to use the latest
'''shell
sudo wget https://github.com/shadowsocks/shadowsocks-rust/releases/download/v1.18.4/shadowsocks-v1.18.4.x86_64-unknown-linux-gnu.tar.xz -O - | sudo tar -xJ -C /usr/local/bin/

### edit or place the json
'''sudo mkdir -p /etc/shadowsocks
'''sudo vim /etc/shadowsocks/config.json

### edit or place the service
sudo vim /etc/systemd/system/shadowsocks.service


'''sudo systemctl daemon-reload #Systemctl reload

sudo systemctl start shadowsocks #start

sudo systemctl enable shadowsocks

sudo systemctl status shadowsocks
---just for fun---
