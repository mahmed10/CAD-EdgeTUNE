# CAD-EdgeTUNE

## Jetson Setup

### Changing the mount point to SSD
https://www.youtube.com/watch?v=ZK5FYhoJqIg
1. Copy git repo ``git clone https://github.com/jetsonhacks/rootOnNVMe``
2. Next, copy the rootfs of the eMMC/SD card to the SSD ``./copy-rootfs-ssd.sh``
3. Then, setup the service. This will copy the .service file to the correct location, and install a startup script to set the rootfs to the SSD ``./setup-service.sh``
4. After setting up the service, reboot for the changes to take effect
