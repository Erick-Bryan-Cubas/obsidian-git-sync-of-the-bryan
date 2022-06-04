O cenário N:1 é voltado para o mercado residencial, com [[autenticação via PPPoE]], DHCP e IPoE. Sua ideia é o atendimento em massa de usuários, em que uma vlan suporta miríades de clientes. 
*Vlan => OLT*
Podendo ser uma vlan para a OLT como um todo, ou seja, uma vlan para autenticar toda a OLT. Autenticação de todos os clientes independentemente da porta gpon. 
*Vlan => PON*
Ou uma vlan por portas PON. Por exemplo:
Porta PON 1 = Vlan 1001
Porta PON 2 = Vlan 1002

*ONUs Isoladas*
No N:1 a ONU não se comunica com outra, sem comunicação através da OLT. 

