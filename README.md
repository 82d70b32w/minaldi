# Minaldi

Minimal custom UI for Vivaldi.

For people who prefer shortcuts and gestures, that is for me. :)

## Vivaldi installation (xbps-src)
```
git clone git://github.com/void-linux/void-packages.git &&
cd void-packages &&
./xbps-src binary-bootstrap &&
echo XBPS_ALLOW_RESTRICTED=yes >> etc/conf &&
./xbps-src pkg vivaldi &&
xbps-install --repository=hostdir/binpkgs/nonfree vivaldi
```

## Enabling support for CSS mods
- Go to “vivaldi://experiments/”
- Tick “Allow for using CSS modifications”

## Loading CSS mods
- Open the browser settings
- Go to “Appearance” and scroll down until you reach “Custom UI Modifications”
- Click on “Select Folder” and select the folder where your CSS mods will be installed
