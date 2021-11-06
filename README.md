# Minaldi

Minimal UI for Vivaldi.

## Vivaldi installation (xbps-src)

```
git clone git://github.com/void-linux/void-packages.git &&
cd void-packages &&
./xbps-src binary-bootstrap &&
echo XBPS_ALLOW_RESTRICTED=yes >> etc/conf &&
./xbps-src pkg vivaldi &&
xbps-install --repository=hostdir/binpkgs/nonfree vivaldi
```
