Wicd-Network-Manager
====================

Linux VPN<br/>

###安装<br/>
apt-get install network-manager-gnome<br/>
apt-get install network-manager-pptp<br/>
apt-get install network-manager-vpnc<br/>
cp /etc/network/interfaces /etc/network/interfaces.backup<br/>
echo "auto lo" > /etc/network/interfaces<br/>
echo "iface lo inet loopback" >> /etc/network/interfaces<br/>
service network-manager restart <br/>

###配置<br/>
添加VPN，在高级设置中勾选 Use Point-to-Poingt encryption(MPPE)<br/>
