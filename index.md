# Attention this is free to use not for sale
# AutoScriptXray
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://install.givpn.my.id/AutoScriptXray.sh && chmod +x AutoScriptXray.sh && sed -i -e 's/\r$//' AutoScriptXray.sh && screen -S setup ./AutoScriptXray.sh
```
Service & Port
<br>
- OpenSSH                  : 22<br>
- SSH Websocket            : 80 [OFF]<br>
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
```
rm -f autoset.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://install.givpn.my.id/autoset.sh && chmod +x autoset.sh && sed -i -e 's/\r$//' autoset.sh && screen -S setup ./autoset.sh
```
Service & Port
<br>
- SlowDNS                   : All Port SSH<br>
- OpenSSH                   : 22, 2253<br>
- Dropbear                  : 443, 109, 143, 1153<br>
- Stunnel5                  : 443, 445, 777<br>
- OpenVPN                   : TCP 1194, UDP 2200, SSL 990<br>
- Websocket SSH TLS         : 443<br>
- Websocket SSH HTTP        : 8880<br>
- Websocket OpenVPN         : 2086<br>
- Squid Proxy               : 3128, 8080 [OFF]<br>
- Badvpn                    : 7100, 7200, 7300<br>
- Nginx                     : 89<br>
- Wireguard                 : 7070<br>
- L2TP/IPSEC VPN            : 1701<br>
- PPTP VPN                  : 1732<br>
- SSTP VPN                  : 444<br>
- Shadowsocks-R             : 1443-1543<br>
- SS-OBFS TLS               : 2443-2543<br>
- SS-OBFS HTTP              : 3443-3543<br>
- XRAYS Vmess TLS           : 8443<br>
- XRAYS Vmess None TLS      : 80<br>
- XRAYS Vless TLS           : 8443<br>
- XRAYS Vless None TLS      : 80<br>
- XRAYS Trojan              : 2083<br>
- XRAYS Vmess GRPC TLS      : 1180,3380<br>
- XRAYS Vless GRPC TLS      : 2280,4480<br>
- OHP SSH                   : 8181<br>
- OHP Dropbear              : 8282<br>
- OHP OpenVPN               : 8383<br>
- Trojan Go                 : 2087<br>
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

# Telegram
[![Telegram-chat](https://img.shields.io/badge/Chat-Telegram-blue)](https://t.me/givpn/)
[![Telegram-grup](https://img.shields.io/badge/Grup-Telegram-blue)](https://t.me/givpn_grup)

YOUR DONATION MAKES ME EXCITED TO LIVE THIS BORING LIFE
# Buy me coffe
[![Saweria donate button](https://img.shields.io/badge/Donate-Saweria-red)](https://saweria.co/givpn11)
[![Ko-fi donate button](https://img.shields.io/badge/Donate-Ko--fi-red)](https://ko-fi.com/givpn11)
[![PayPal donate button](https://img.shields.io/badge/Donate-PayPal-blue)](https://paypal.me/givpn11)
# LICENSE
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
