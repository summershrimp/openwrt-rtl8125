# OpenWRT Repository for rtl8125

## Support

Realtek RTL8125 series 2.5GBE pcie network card.
 - RTL8125a
 - RTL8125b

## Usage
```
echo 'src-git rtl8125 https://github.com/summershrimp/openwrt-r8125.git;master' >> feeds.conf.default
./script/feeds update -a
./script/feeds install -a
```
