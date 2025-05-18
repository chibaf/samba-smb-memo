# samba on raspbian

sudo apt install samba

sudo vi /etc/samba/smb.conf

sudo service smbd restart

mbpasswd -a pi

sudo smbpasswd -a pi
