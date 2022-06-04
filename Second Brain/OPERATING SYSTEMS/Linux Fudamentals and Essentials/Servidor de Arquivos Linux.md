# HOW TO
#Instalando
Samba: sudo apt-get install samba samba-common 
#Adicionando
meu usuario ao samba: sudo smbpasswd -a seu_Usuario 
#Fazendo
Backup do smb.conf: sudo cp /etc/samba/smb.conf /etc/samba/smb.conf.old 
#Editando
smb.conf: gedit /etc/samba/smb.conf 
#Localize
As definições de compartilhamento 
 ! = colchete 
 !Downloads! 
 comment = Downloads 
 path = /home/danegd/Downloads/ 
 guest ok = no 
 browseable = yes 
 create mask = 0600 
 directory mask = 0700 
#Iniciando
service smbd start/stop