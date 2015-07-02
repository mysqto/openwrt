### Welcome to Mysqto's OpenWrt Mirror.

This is the personal OpenWrt package mirror maintained by [@Mysqto](https://github.com/mysqto). Currently hosted the following packages for ramips(Xiaomi Wifi Mini) based on the OpenWrt official snapshot builds:

 Name                     | Description
 -------------------------|-----------------------------------
 [redsocks][1]            | redsocks(With OpenSSL) for OpenWRT
 [openwrt-chinadns][2]    | ChinaDNS-C for OpenWRT
 [openwrt-shadowvpn][3]   | ShadowVPN for OpenWrt
 [openwrt-dnsmasq][4]     | Dnsmasq Patch & Makefile for OpenWrt
 [openwrt-shadowsocks][5] | Shadowsocks-libev for OpenWrt
 [openwrt-dist-luci][6]   | LuCI Applications for OpenWrt-dist

### Uasge
Add the following line to your `/etc/opkg.conf` file

```
src/gz openwrt_dist http://dist.openwrt.link/releases/ramips/mt7620/packages/base
```

And run 'opkg update' to update the package source.

Enjoy the free internet.


  [1]: https://github.com/semigodking/redsocks
  [2]: https://github.com/clowwindy/ChinaDNS
  [3]: https://github.com/clowwindy/ShadowVPN
  [4]: https://github.com/semigodking/redsocks
  [5]: https://github.com/shadowsocks/openwrt-shadowsocks
  [6]: https://github.com/aa65535/openwrt-dist-luci
