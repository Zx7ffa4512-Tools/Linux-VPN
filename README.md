Wicd-Network-Manager
====================

Linux VPN

#安装
apt-get install network-manager-gnome
apt-get install network-manager-pptp
apt-get install network-manager-vpnc
cp /etc/network/interfaces /etc/network/interfaces.backup
echo "auto lo" > /etc/network/interfaces
echo "iface lo inet loopback" >> /etc/network/interfaces
service network-manager restart 

#配置
添加VPN，在高级设置中勾选 Use Point-to-Poingt encryption(MPPE)
