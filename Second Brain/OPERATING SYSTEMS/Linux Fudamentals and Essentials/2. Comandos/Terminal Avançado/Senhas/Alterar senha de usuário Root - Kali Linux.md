# Como alterar a senha do usuário Root no Kali Linux 
Na inicialização do sistema operacional no [[GRUB]] selecione *Advanced options for Kali GNU/Linux* e clique em E para editar
Em seguida procure por:

if
echo 'Loandig Linux ...'
linux /boot/vmlinuz ... [[ro quiet splash]]

Delete *ro quiet splash*
Substitua por [[rw init=/bin/bash]]

aperte F10 para salvar as alterações 

no terminal digite [[passwd]]]
e por fim escolha a senha. 

root