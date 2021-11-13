To use this repository issue the following commands as root:

```
mkdir -p /usr/local/etc/pkg/repos/
echo 'Katana: { url: "pkg+https://raw.githubusercontent.com/fluxer/katana-freebsd/master", mirror_type: "srv", enabled: yes }' > /usr/local/etc/pkg/repos/Katana.conf
pkg update
pkg install katana-workspace
```
