# AutoScriptXray
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://install.givpn.my.id/AutoScriptXray.sh && chmod +x AutoScriptXray.sh && sed -i -e 's/\r$//' AutoScriptXray.sh && screen -S setup ./AutoScriptXray.sh
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
-Step 1
```
sudo su
```
-Step 2
```
cd
```
-Step 3
```
apt update && apt install wget -y && wget -qO- -O rootvps.sh https://install.givpn.my.id/rootvps.sh && bash rootvps.sh
  
```
# Step 4 install
```
rm -f autoset.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://install.givpn.my.id/autoset.sh && chmod +x autoset.sh && sed -i -e 's/\r$//' autoset.sh && screen -S setup ./autoset.sh
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

# Aio
# Setup DNS Cloudflare
![cf](https://raw.githubusercontent.com/dugong-lewat/autoscript/main/cf.jpg)

# Installation
- via WGET
```
bash -c "$(wget -qO- https://install.givpn.my.id/aio)"
```
- via CURL
```
bash -c "$(curl -fsSL https://install.givpn.my.id/aio)"
```

|  SERVICE  |  NETWORK PORT  |
|---------- |--------|
| Vmess WS TLS (multipath)  | 443 |
| Vless WS TLS  | 443 |
| Trojan WS TLS  | 443 |
| Socks5 WS TLS  | 443 |
| Shadowsocks WS TLS (aes-256-gcm)  | 443 |
| Shadowsocks 2022 WS TLS (2022-blake3-aes-256-gcm)  | 443 |
| Vmess WS (multipath)  | 80 |
| Vless WS  | 80 |
| Trojan WS  | 80 |
| Socks5 WS  | 80 |
| Shadowsocks WS (aes-256-gcm)  | 80 |
| Shadowsocks 2022 WS (2022-blake3-aes-256-gcm)  | 80 |
| Vmess gRPC  | 443 |
| Vless gRPC  | 443 |
| Trojan gRPC  | 443 |
| Socks5 gRPC  | 443 |
| Shadowsocks gRPC (aes-256-gcm)  | 443 |
| Shadowsocks 2022 gRPC (2022-blake3-aes-256-gcm)  | 443 |
| Nginx Webserver | 8000 |
| Auto Delete Expired Account | ✅ |
| DNS Setting | ✅ |

|  ALTERNATIF PORT  |  NETWORK PORT  |
|-------------------|--------|
| HTTPS  | 2053, 2083, 2087, 2096, 8443 |
| HTTP  | 8080, 8880, 2052, 2082, 2086, 2095 |

# aioV2 revision beta test
# Create root on the VPS for those of you who log into the server still using a username that isn't root
- Step 1
  ```
  sudo su
  ```
- Step 2
   ```
   cd
   ```
- Step 3
  ```
  apt update && apt install wget -y && apt upgrade -y && apt dist-upgrade -y && wget -qO- -O rootaioV2.sh https://install.givpn.my.id/rootaioV2.sh && bash rootaioV2.sh
  ```
## Step 4 Install

  ```
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://install.givpn.my.id/aioV2.sh && chmod +x aioV2.sh && sed -i -e 's/\r$//' aioV2.sh && screen -S setup ./aioV2.sh
  ```
# Service & Port:
<br>
  - OpenSSH                      : 22<br>
  - OpenVPN                      : TCP 1194, UDP 2200, SSL 110<br>
  - Stunnel4                     : 222, 777<br>
  - Dropbear                     : 143, 109<br>
  - OHP Dropbear                 : 8585<br>
  - OHP SSH                      : 8686<br>
  - OHP OpenVPN                  : 8787<br>
  - Websocket SSH(HTTP)          : 80<br>
  - Websocket SSL(HTTPS)         : 443, 2096<br>
  - Websocket OpenVPN            : 2097<br>
  - SSH UDP                      : 1-65535<br>
  - Squid Proxy                  : 3128, 8000<br>
  - Badvpn                       : 7100, 7200, 7300<br>
  - Nginx                        : 81<br>
  - XRAY Vmess Ws Tls            : 443<br>
  - XRAY Vless Ws Tls            : 443<br>
  - XRAY Trojan Ws Tls           : 443<br>
  - XRAY Socks5 Ws Tls           : 443<br>
  - XRAY Shadowsocks Ws Tls      : 443<br>
  - XRAY Vless Tcp Xtls          : 443<br>
  - XRAY Trojan Tcp Tls          : 443<br>
  - XRAY Vmess Ws None Tls       : 80<br>
  - XRAY Vless Ws None Tls       : 80<br>
  - XRAY Trojan Ws None Tls      : 80<br>
  - XRAY Socks5 Ws None Tls      : 80<br>
  - XRAY Shadowsocks Ws None Tls : 80<br>
<br>
# Server Information & Other Features:
<br>
   - Timezone                 : Asia/Jakarta (GMT +7)<br>
   - Fail2Ban                 : [ON]<br>
   - DDOS Dflate              : [ON]<br>
   - IPtables                 : [ON]<br>
   - Auto-Reboot              : [ON]- 01.00 GMT +7<br>
   - Auto-Remove-Expired      : [ON]<br>
   - IPv6                     : [OFF]<br>
   - Auto Delete Expired Account<br>
   - Fully automatic<br>
   - VPS settings<br>
   - Admin Control<br>
   - Change port<br>
   - Full Orders For Various Services<br>
<br>

# Telegram
[![Telegram-chat](https://img.shields.io/badge/Chat-Telegram-blue)](https://t.me/givpn/)
[![Telegram-grup](https://img.shields.io/badge/Grup-Telegram-blue)](https://t.me/givpn_grup)

YOUR DONATION MAKES ME EXCITED TO LIVE THIS BORING LIFE
# Buy me coffe
[![Saweria donate button](https://img.shields.io/badge/Donate-Saweria-red)](https://saweria.co/givpn11)
[![Ko-fi donate button](https://img.shields.io/badge/Donate-Ko--fi-red)](https://ko-fi.com/givpn11)
[![PayPal donate button](https://img.shields.io/badge/Donate-PayPal-blue)](https://paypal.me/givpn11)
<a href="https://www.digitalocean.com/?refcode=8a474003bf18&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge"><img src="https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg" alt="DigitalOcean Referral Badge" /></a>
# LICENSE
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
<p align="center">
  <a><img src="https://img.shields.io/badge/givpn-Auto_script_VPS%202023-blue" style="max-width:200%;">
<p align="center">
  <a><img src="https://img.shields.io/badge/Attention_this_is_free_to_use_not_for_sale%20-blue" style="max-width:200%;">
  
   
