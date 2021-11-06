# Minaldi

Minimal UI for Vivaldi.

## Vivaldi via xbps-src

```
#!/bin/sh
git clone git://github.com/void-linux/void-packages.git &&
cd void-packages &&
./xbps-src binary-bootstrap &&
echo XBPS_ALLOW_RESTRICTED=yes >> etc/conf &&
./xbps-src pkg vivaldi &&
xbps-install --repository=hostdir/binpkgs/nonfree vivaldi &&
# Local repository to the xbps settings
echo 'repository=/home/me/void-packages/hostdir/binpkgs/nonfree' > /etc/xbps.d/10-local.conf
# Remove packages from previous versions of local repository
# xbps-rindex -r /home/me/xbps-packages/hostdir/binpkgs/nonfree
```
