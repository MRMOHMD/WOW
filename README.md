#Warp on Warp (MOBILE)
1) IP/Ports of the Cloudflare Warp (termux)-scanner
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```
2) Termux
```
bash <(curl -fsSL https://raw.githubusercontent.com/bepass-org/warp-plus/master/termux.sh)
```
3) Cloudflare Account
```
curl -sL "https://api.zeroteam.top/warp?format=sing-box" | grep -Eo --color=never '"2606:4700:[0-9a-f:]+/128"|"private_key":"[0-9a-zA-Z\/+]+="|"reserved":\[[0-9]+(,[0-9]+){2}\]'
```
