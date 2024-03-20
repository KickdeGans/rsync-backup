# rsync-backup
## A simple tool for backing up your files to a samba share
### Quick example:
```shell
rsync-backup sync
```
### Example config:
```config
username=user
location=/my-backup
backup-location=/home/user/
server=123.123.123.123
excludes={
    exclude.txt
    exclude2.txt
}
```
### Installation: 
```shell
./install.sh
```
