# rsync-backup
## A simple tool for backing up your files to a samba share
### Quick example:
```shell
rsync-backup sync
```
### Example config:
```config
username=user
password=myPassword
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
#### Dependecies:
```
ssh
sshpass
rsync
python3
```
Debian (also systems like ubuntu, mint etc.):
```
sudo apt install ssh sshpass rsync python3
```
Arch linux:
```
sudo pacman -S ssh sshpass rsync python3
```
Redhat (also systems like fedora):
```
sudo dnf install ssh sshpass rsync python3
```
