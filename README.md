# docker-vaultwarden
Alt Bitwarden


### Recovery from backup:
```bash
BACKUPFILE=/path/to/backup-file.tar.xz
RESTORELOCATION=/path/to/vaultwarden/data
sudo tar -xvf $BACKUPFILE -C $RESTORELOCATION
```