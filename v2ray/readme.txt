执行命令：
wget https://raw.githubusercontent.com/v2fly/fhs-install-v2ray/master/install-release.sh

sudo chmod 755 install-release.sh

sudo bash install-release.sh

config.json 上传至 /usr/local/etc/v2ray
sudo mv config.json /usr/local/etc/v2ray/config.json
sudo chmod 755 /usr/local/etc/v2ray/config.json

sudo systemctl enable v2ray

sudo systemctl start v2ray