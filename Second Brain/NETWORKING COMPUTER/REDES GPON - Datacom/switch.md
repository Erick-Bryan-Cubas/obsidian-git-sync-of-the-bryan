## Característica Switch 
1. Wire speed, chipset dedicado para realizar grande parte de suas funções;
2. Integração com redes *Metro Ethernet*;
OLT ==> Switch ==> Concentrador ==> Internet 
3. Possibilidade de configuração de 4.094 VLANs de forma simultânea;
Não nehuma Vlan restrita ou reservada, todas as de ID do 1 ao 4094 estão disponíveis simultaneamente. Adotando todos os requisitos do IEEE 802.1, que aborda sobre as Vlans.  
4. QinQ - IEEE 802.1ad Provider Bridge e Vlan translate. 
O Vlan translate permite converter uma vlan captada de ID, por exemplo, ID 20 para ID 2000.
5. SNMP v1, v2 e v3;
6. Proteção de loop com a família de protocolos STP, EAPS e ERPS;
STP ==> ESTP e MSTP, ambos com tempo de convergência de até 20 segundos; 
EAPS E ERPS ==> Protocolos abertos com tempo de convergência de até 50mseg;
7. Mecanismos de segurança com RADIUS e TACACS+
O Radius é para realizar a gestão dos administradores de rede, ou seja, definir os usuários que poderão acessar o equipamento. 
SN1 - show
SN2 - show + config 
SN3 - Root
As regras são resumidas em AAA: 
*A*utenticação: permissão para acessar o equipamento
*A*utorização: o que pode ser feito;
*A*ncount: contabilização, o que foi feito e quais comandos fora executado. 
8. Controle de *Storm Control*;
9. Link Aggregation estático e LACP (dinâmico); 
O Link Aggregation é utilizado para servir de base paliativa, quando há um rompimento de uma das extremidades. Criando também uma única interface para dispositivos divergente; 
LACP ==> Link Aggregation Control Protocol 
10. QoS - qualidade de serviços 
QoS ==> ACL (filtros, o que é permitido. Qual vlan, qual tipo de tráfego...);
Rate Limit ==> limitação de banda em uma vlan específica; 
11. Roteamento estático e dinâmico 
Dinâmico ==> OSPF 
12. MPLS L2VPN:
VPWS = P2P (ponto à ponto, matriz e filial) 
VPLS = Multiponto e Mesh. 