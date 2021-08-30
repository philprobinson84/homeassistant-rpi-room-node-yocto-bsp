# Boxtree HomeAssistant Yocto BSP

## How to use the BSP

### Downloading

Download all the git repositories for Bitbake and the required Yocto layers (as specified by the manifest in this repository):

```bash
mkdir ~/yocto_boxtree_rpi
cd ~/yocto_boxtree_rpi
repo init -u ssh://git@github.com/philprobinson84/homeassistant-rpi-room-node-yocto-bsp.git -b dunfell
repo sync
```
