AutoScriptXray
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/givpn/AutoScriptXray/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
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

# Telegram
[![Telegram-chat](https://img.shields.io/badge/Chat-Telegram-blue)](https://t.me/givpn/)
[![Telegram-grup](https://img.shields.io/badge/Grup-Telegram-blue)](https://t.me/givpn_grup)

# Buy me coffe
[![Saweria donate button](https://img.shields.io/badge/Donate-Saweria-red)](https://saweria.co/givpn11)
[![Ko-fi donate button](https://img.shields.io/badge/Donate-Ko--fi-red)](https://ko-fi.com/givpn11)
[![PayPal donate button](https://img.shields.io/badge/Donate-PayPal-blue)](https://paypal.me/givpn11)
