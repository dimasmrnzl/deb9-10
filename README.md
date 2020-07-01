# Debian 9 and10
Script autoinstall Debian 9 and 10

# Open Ports
<br>OpenSSH  : 22,225
<br>Dropbear : 143,456
<br>SSL      : 443,444
<br>OpenVPN  : 110
<br>Squid    : 80,8080
<br>Badvpn   : 7500
<br>Nginx    : 86
<br>Download : http://$IPADDR:86/janda.zip

# Installation

apt-get install wget -y && wget -q 'https://raw.githubusercontent.com/janda09/deb9-10/master/Debian9-10' && chmod +x Debian9-10 && ./Debian9-10
