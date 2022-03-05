# Node-Termios
## Node Modules For Openwrt

Access Termios settings from nodejs. The module exports a Termios class, that encapsulates termios struct data.

### Usage
Use Openwrt SDK or Build system.

`/script/feeds update -a`
`/script/feeds install -a`
`make menuconfig`
`make package/node-termios/compile -j4 V=sc`

pm2 cron startup :
- `npm install pm2`
- `chmod +x bot.sh`
- add startup config `

### References
- https://github.com/nxhack/openwrt-node-packages