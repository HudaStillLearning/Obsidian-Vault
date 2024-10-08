## bind
```zsh
sudo mkdir -p /mnt/data/apalah
sudo rsync -av /home/kz/apalah/* /mnt/data/apalah/
rm -rf /home/kz/apalah/*
sudo mount --bind /mnt/data/apalah /home/kz/apalah
sudo vim /etc/fstab
	/mnt/data/apalah /home/kz/apalah none bind 0 0
		or
	/mnt/data/apalah /home/kz/apalah none bind,rw,relatime 0 0
sudo systemctl daemon-reload
sudo mount -a
```
## Check bind
```
findmnt /home/kz/apalah
mount | grep /home/kz/apalah
```