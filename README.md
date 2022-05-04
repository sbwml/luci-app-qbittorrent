qBittorrent - A BitTorrent client in Qt6
------------------------------------------

## How to build

Enter in your openwrt/package/ or other

### Openwrt official SnapShots

```shell
git clone https://github.com/sbwml/openwrt-qBittorrent
make menuconfig # choose LUCI -> Applications -> luci-app-qbittorrent
make V=s
```
