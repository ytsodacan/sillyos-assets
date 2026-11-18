# sillyos-assets

Media for SillyOS.

- `wallpapers/`: animated wallpapers (`.mp4` plus a `.jpg` poster for each)
- `decorations/`: avatar decorations (`pack/` holds the full set)
- `effects/`: profile effects

## Install on the server

```bash
git clone --depth 1 https://github.com/ytsodacan/sillyos-assets /tmp/sa
sudo cp -r /tmp/sa/wallpapers/. /opt/sillyos/wallpapers/
sudo cp -r /tmp/sa/decorations/. /opt/sillyos/assets/cherri/deco/
sudo cp -r /tmp/sa/effects/. /opt/sillyos/assets/cherri/effects/
sudo chown -R sillyos:sillyos /opt/sillyos/wallpapers /opt/sillyos/assets/cherri
```
