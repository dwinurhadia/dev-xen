This is readme file
## Dev-XEN Hypervisor
Xen is an open source virtual machine monitor for x86-compatible computers. XenSource Inc. and Virtual Iron Software Inc. promoted Xen as the primary open source competitor to commercial virtualization products such as VMWare

## Installation in Debian 8
apt-get install xen-linux-system

xen-create-image --size=20G \
--swap=1024M \
--memory=3G \
--ip=10.13.245.72 \
--netmask=255.255.0.0 \
--gateway=10.13.1.254 \
--nameserver=10.13.10.13 \
--dir=/mnt/storage/ \
--hostname=vm03 \
--password=noc-123


## License

A short snippet describing the license (Xen, etc.)
# this is nice readme

#Adipati79
