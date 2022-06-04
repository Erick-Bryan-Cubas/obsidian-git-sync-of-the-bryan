### DM4610 OLT GPON
==DM4610 OLT 4GPON + 4GX + 2 XS (HW2)==
Esta OLT possui:
	1) 4 portas GPON do tipo SC/PC (SC do tipo polimento PC)
	2) 4 portas *ópticas 1000Base-X* (SFP) 
		2.1. SFP óptico ethernet;
		2.2. SFP RJ-45/ SFP Elétrico;
	3) 2 portas *´ópticas 10G Base-X* (SFP+)
		3.1. SFP+ / SFP Plus
	4) 1 porta *console* para gerência via serial [[RS232]]
		4.1. O cabo RS232, com uma das extremidades DB9 (computador) e RJ-45 (OLT)
	5) 1 porta MGMT
		Interface com endereço padrão 192.168.0.25/24 (Classe C)
		SSH com login: admin, senha: admin
		O primeiro acesso ao equipamento  só pode ser feito via SSH ou Console. Após isso, pode ser ajustado à configurações via Telnet 
	6) 2 entradas para alimentação AC ou DC Hot-swappable 
	
---
Capacidade de *comutação* de 63 Gbit/s 
Encaminhamento de até 46Mpps (milhões de pacotes por segundo)
Tabela de aprendizado de [[MAC]] para 64k endereços. 

---
*Switch fabric* ou a capacidade de comutação é a _capacidade que o backplane do equipamento possui_. Da OLT de 4 portas GPON é de 63TGbits. Equipamento não blocante, sem nenhuma capacidade de bloqueio. Portanto, sendo pleno. 
Sendo:
_PORTAS GPON_
4 x 2,5G (downstream) = 10G
4 x 1,25G (upstream) = 5G
_PORTAS ETHERNET 1G_
4 x 1G x 2 (Tx e Rx) = 8G
_PORTAS ETHERNET 10G_
2 x 10G x 2 (Tx e Rx) = 40G

---
*Wire speed* é o processamento de pacotes em hardware. ou seja, com chipset dedicado para a comutação de pacotes. 
Circunstâncias de operação da CPU: 
1. Aprendizado de um novo endereço MAC; 
2. Uma VLAN com endereçamento IP, geralmente utilizada para gerência/ gestão do equipamento;
3. As mensagens de controles dos protocolos. O pacote de controle do OSPF é o "hello"
---

##  DM4610 OLT GPON 
*DM4610 OLT 8GPON + 8GX +8GX + 4GT + 2XS*
1) 8 portas GPON (SC/PC);
2) 8 portas  ópticas 1000Base-X (SFP);
3) 4 portas 10/100/1000Base-T (RJ-45);
4) 2 portas ópticas 10G Base-X (SFP+)
5) 1 porta CONSOLE para gerência via serial RS232
6) 1 porta MGMT (IP de acesso: 192.168.0.25/24)
7) 2 entradas para alimentação AC ou DC Hot-swappable 
_portas ímpares em baixo e pares para cima_
Capacidade de comutação de 94Gbits/s
Encaminhamento de até 70Mpps
Tabela de aprendizado de MAC para 64k endereços 

---
## DM4615 OLT 16GPON + 4GT + 4 XS
1) 16 portas GPON (SC/PC)
2) 4 portas 10/100/1000Base-T (RJ-45)
3) 4 portas ópticas 10G Base-X (SFP+)
4) 1 porta CONSOLE para gerência via serial RS232
5) 1 porta MGMT 
6) 2 entradas para alimentação AC ou DC Hot-swappable
1. Principal
2. Secundária 
Capacidade de comutação de 148Gbit/s;
Encaminhamento de até 110Mpps;
Tabela de aprendizado de MAC para 64k endereços. 
