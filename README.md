
 **For any issues**

> Welcome share and correct.
>
> Thanks!

##USAGE

### backup and restore your app list

>backup

`sudo dpkg--get-selections > app-backup-list`

>restore

    sudo dpkg--set-selections

    sudo apt-get -y update

    sudo apt-get dselect-upgrade

