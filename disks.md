sudo mkdir -p /mnt/nebula
sudo mkdir -p /mnt/andromeda

UUID=id /mnt/nebula ext4 defaults,noatime,x-gvfs-show,x-gvfs-name=Nebula,user 0 2
UUID=id /mnt/andromeda ext4 defaults,noatime,x-gvfs-show,x-gvfs-name=Andromeda,user 0 2

sudo chown -R klm:klm /mnt/Nebula
sudo chown -R klm:klm /mnt/Andromeda
