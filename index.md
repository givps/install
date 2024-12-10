# NOTE
<br>
- make sure the vps provider allows the use of Public VPN/SSH/Proxy<br>
- Required VPS is still fresh (MUST) / have never installed anything<br>
- If you install the Script twice, you need to rebuild the VPS to factory settings, in the VPS provider panel<br>
<br>

# AutoScriptXray
[![repo](https://img.shields.io/badge/repo-AutoScriptXray-blue)](https://github.com/givps/AutoScriptXray)
- install
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givps/AutoScriptXray/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
Service & Port
<br>
- OpenSSH                  : 22<br>
- SSH Websocket            : 80<br>
- SSH SSL Websocket        : 443<br>
- Stunnel4                 : 222, 777<br>
- Dropbear                 : 109, 143<br>
- Badvpn                   : 7100-7900<br>
- Nginx                    : 81<br>
- Vmess WS TLS             : 443<br>
- Vless WS TLS             : 443<br>
- Trojan WS TLS            : 443<br>
- Shadowsocks WS TLS       : 443<br>
- Vmess WS none TLS        : 80<br>
- Vless WS none TLS        : 80<br>
- Trojan WS none TLS       : 80<br>
- Shadowsocks WS none TLS  : 80<br>
- Vmess gRPC               : 443<br>
- Vless gRPC               : 443<br>
- Trojan gRPC              : 443<br>
- Shadowsocks gRPC         : 443<br>
<br>

# Autoset
[![repo](https://img.shields.io/badge/repo-Autoset-blue)](https://github.com/givps/autoset)
- install
```
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givps/autoset/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
Service & Port
<br>
- SlowDNS SSH             : ALL Port SSH<br>
- OpenSSH                 : 22<br>
- OpenVPN                 : TCP 1194, UDP 2200, SSL 990<br>
- Stunnel5                : 443, 445<br>
- Dropbear                : 443, 109, 143<br>
- SSH Websocket TLS       : 443<br>
- SSH Websocket HTTP      : 8880<br>
- Websocket OpenVPN       : 2086<br>
- Squid Proxy             : 3128, 8080<br>
- Badvpn                  : 7100, 7200, 7300<br>
- Nginx                   : 89<br>
- Wireguard               : 7070<br>
- L2TP/IPSEC VPN          : 1701<br>
- PPTP VPN                : 1732<br>
- SSTP VPN                : 444<br>
- Shadowsocks-R           : 1443-1543<br>
- SS-OBFS TLS             : 2443-2543<br>
- SS-OBFS HTTP            : 3443-3543<br>
- XRAYS Vmess TLS         : 8443<br>
- XRAYS Vmess None TLS    : 80<br>
- XRAYS Vless TLS         : 8443<br>
- XRAYS Vless None TLS    : 80<br>
- XRAYS Trojan            : 2083<br>
- XRAYS VMESS GRPC        : 1180<br>
- XRAYS VLESS GRPC        : 2280<br>
- OHP SSH                 : 8181<br>
- OHP Dropbear            : 8282<br>
- OHP OpenVPN             : 8383<br>
- TrojanGo                : 2087<br>
<br>

# Telegram
[![Telegram](https://img.shields.io/badge/Telegram-Grup-blue)](https://t.me/givpn_grup/)

YOUR DONATION MAKES ME EXCITED TO LIVE THIS BORING LIFE
# Buy me coffe
<!--[![PayPal donate button](https://img.shields.io/badge/Donate-PayPal-yellow)](https://paypal.me/givpn11)
[![QRIS donate button](https://img.shields.io/badge/Donate-QRIS-red)](https://raw.githubusercontent.com/givpn/AutoScriptXray/master/image/qris-givpn.jpg)
[![Bitcoin donate button](https://img.shields.io/badge/Donate-Bitcoin-orange)](https://www.blockchain.com/explorer/addresses/btc/3BE1deCJcuykuTHMzmrmNYgN51E24Hix8i)-->
[![Ethereum donate button](https://img.shields.io/badge/Donate-Ethereum-blue)](https://www.blockchain.com/explorer/addresses/eth/0x3eb09df9a72e8e333e202116ff3eb348b3ebf554)

<!-- <a href="https://www.digitalocean.com/?refcode=8a474003bf18&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge"><img src="https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg" alt="DigitalOcean Referral Badge" /></a> -->
<p align="center">
<a href="https://opensource.org/licenses/MIT"> <img src="https://img.shields.io/badge/License-MIT-yellow.svg" style="max-width:200%;"> <a><img src="https://img.shields.io/badge/Auto_Script_VPS-blue" style="max-width:200%;">
<p align="center">
  <a><img src="https://img.shields.io/badge/Attention_this_is_free_to_use_not_for_sale%20-critical" style="max-width:200%;">
  
   
