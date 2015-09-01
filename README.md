Wicd-Network-Manager
====================

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







Kali2.0 Linux安装VPN
====================
    apt-get install -y network-manager-openvpn-gnome network-manager-pptp network-manager-pptp-gnome network-manager-vpnc network-manager-vpnc-gnome<br/>

###配置<br/>
    勾选MPPE,PPP回响<br/>
