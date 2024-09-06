# 02 nfs share
```bash
sudo apt install nfs-common
sudo mkdir /mnt/nfs
```

```bash
sudo nano /etc/fstab  
```
```
10.1.10.80:/mnt/NVME/NFSshare /mnt/nfs nfs4 defaults 0 0
```
```bash
sudo reboot now
```

```bash
sudo ls /mnt/nfs
```