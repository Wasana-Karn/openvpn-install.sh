# openvpn-install.sh
OpenVPN Install Script
mkdir openvpn
cd openvpn/
wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
cd /root
mkdir openvpn
cd openvpn/
ls -lah
cd /root/
mv tecmobai.ovpn openvpn/
cd openvpn/
ls -lah
vi tecmobai.ovpn
sh openvpn-install.sh
bash openvpn-install.sh
ls -lah
service openvpn status
service openvpn start
service openvpn status
