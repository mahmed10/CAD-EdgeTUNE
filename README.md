# CAD-EdgeTUNE

## Jetson Setup

### Changing the mount point to SSD
https://www.youtube.com/watch?v=ZK5FYhoJqIg
1. Copy git repo ``git clone https://github.com/jetsonhacks/rootOnNVMe``
2. cd rootOnNVMe
3. Next, copy the rootfs of the eMMC/SD card to the SSD ``./copy-rootfs-ssd.sh``
4. Then, setup the service. This will copy the .service file to the correct location, and install a startup script to set the rootfs to the SSD ``./setup-service.sh``
5. After setting up the service, reboot for the changes to take effect


https://developer.nvidia.com/embedded/linux-tegra-r3271

https://catalog.ngc.nvidia.com/orgs/nvidia/containers/l4t-ml

https://gist.github.com/jetsonhacks/2717a41f7e60a3405b34


sudo apt-get install qemu-user-static
