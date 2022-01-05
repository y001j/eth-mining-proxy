# Deployed ETH mining proxy：可以使用的部署好的ETH代理地址:
f2pool/鱼池: 139.196.181.234:1081
ethermine: 139.196.181.234:1088

# eth-mining-proxy
It is a ethereum mining proxy tool that help minners who cannot directly connect to a mining pool 

**example：**

use socks5 proxy ，run command line: 

`miningproxy 0.0.0.0 1081 asia2.ethermine.org:4444 127.0.0.1:9788`

`0.0.0.0 1081`  is mining proxy port and binding ip address in host

`asia.ethermine.org:4444 ` is  mining  pool  address

`127.0.0.1:9788` is socks5 proxy address, if use V2ray or shadowsocks，you can put  local http proxy address.

If you don't need socks5 proxy, run command line: 

`miningproxy 0.0.0.0 1081 asia2.ethermine.org:4444 `

just remove socks5 proxy address

if the mining proxy is running on local PC, you can mining towards 127.0.0.1:1081 as pool address.

