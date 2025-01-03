
### ZFS POOL 

https://ubuntu.com/tutorials/setup-zfs-storage-pool#3-creating-a-zfs-pool

RAID5 group of disk 

apt-get install zfsutils-linux

zpool create archive-sdd /dev/sdd

zfs set mountpoint=/srv/node/sdd archive-sdd

zfs set compression=on archive-sdd

zpool list



