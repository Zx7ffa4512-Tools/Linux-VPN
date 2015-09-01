Wicd-Network-Manager
====================

**安装**<br/>

    apt-get install network-manager-gnome
    apt-get install network-manager-pptp
    apt-get install network-manager-vpnc
    cp /etc/network/interfaces /etc/network/interfaces.backup
    echo "auto lo" > /etc/network/interfaces
    echo "iface lo inet loopback" >> /etc/network/interfaces
    service network-manager restart 

**配置**<br/>

    添加VPN，在高级设置中勾选 Use Point-to-Poingt encryption(MPPE)


<br/><br/><br/>




Kali2.0 Linux安装VPN
====================
**安装**<br/>

    apt-get install -y network-manager-openvpn-gnome network-manager-pptp network-manager-pptp-gnome network-manager-vpnc network-manager-vpnc-gnome

**配置**<br/>

    勾选MPPE,PPP回响
