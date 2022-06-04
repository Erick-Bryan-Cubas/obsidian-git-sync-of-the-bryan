### Classificação das redes 
A divisão da conectividade das redes é realizada por **modelo computacional**, **abrangência** e **topologia** 

 	Por abrangência
		PAN (Personal Area Network): rede de alcance a 1m (até 10m) por pessoa, intermediario de conectividade ausente. 
			a. curta distância;
			b. conecta dois nós entre si;
			c. envolve poucos equipamentos; 
			d. não depende de intermediários. 
		LAN (Local Area Network): dispositivos conectados no mesmo ambiente físico por meio de cabeamentos ethernet ou wireless. Distância de até 100m 
			a. mesmo ambiente físico; 
			b. curta distância; 
			c. altas velocidades; 
			d. conecta vários nós entre si;
			e. poucos equipamentos obrigatórios (switch/hub)
		CAN (Campus Area Network): conectividades entre redes locais. Distância de até 1Km. 
			a. interligação entre redes locais; 
			b. distância moderada; 
			c. velocidade moderada; 
			d. maior necessidade de infraestrutura e equipamentos; 
		MAN (Metropolitan Area Network): tecnologias restritas. Distância de 10Km para mais. Necessita de poucas tecnologias e protocolos. 
			a. interliga bairros, cidades, e estados;
			b. grandes distâncias;
			c. velocidade limitada;
			d. grande necessidade de infraestrutura. 
		WAN (Wide Area Network): de 1000Km para mais. Interconeta países e globos. Requer um número maior de tecnologias e protocolos. 
			a. interliga redes distribuídas geograficamente; 
			b. distâncias continentais; 
			c. velocidade limitada; 
			d. necessita de várias tecnologias para permitir a conexão. 
			
Topologia é a forma física de um objeto ou de seu conjunto. A topologia de redes de computadores coexiste de forma **lógica** ou **física**. 
	Meios físcos de transmissão: ponto a ponto. Nó (ponto de comunicação na rede) enlace (meio físico para conectar os nós). PTP é um enlace conectando dois nós. 
	
Os tipos de transmissão é a forma como os sinais são enviados no enlance. 
	
		Transmissão **simplex**: sinal unidirecional. Uma única direção
		Transmissão **half-duplex**: transmisão em ambas direções, não simultâneo. 
		Transmissão **full-duplex**: transmissão em ambas direções simultâneamente. 

Formas físicas de conectividade entre as máquinas:

		a. Topologia estrela: um equipamento central (hub, switch, roteador e servidor) intermediário da comunicação. O comando central direciona as informações. O meio físico de transmissão é somente PTP. 
			HUB: half-duplex;
			SWITCH, ROTEADOR E SERVIDOR: full-duplex. 
		A topologia estrela suporta três tipos de cabos:
			Par-trançado
			Coaxial
			Fibra óptica
		Com 4 tipos de tecnologias lógicas: 
			ethernet (10Mbps) Padrão IEEE: 802.3; 
			fast-ethernet (100Mbps) Padrão IEEE: 802.3u ;
			gigabit ethernet (1000Mbps) Padrão IEEE: 802.3z 
			10 gigabit ethernet (10000Mbps) Padrão IEEE: Padrão IEEE: 802.3ab
			
		b. a topologia em anel conecta host formando um sistema fechado. Sendo PTP. Sinal simplex, ou seja, se for orientada a uma direção a seguirá unicamente. Todos computadores atuam como repetidores de sinais, uma comunicação por vez. Sendo possível conectar de duas formas: atrvés de um cabeamento formando um circuito fechado entre os hosts ou com a utilização de um MAU (Multistation Access Unit, os dados são transmitidos por meio das portas do dispositivo seguindo o padrão anel)
			Tipos de cabos: 
				par-trançado 
				fibra-óptica
			Tipos de tecnologia aplicadas: 
				token ring (4mbps-16Mbps) Padrão IEEE: 802.5
				FDDI (100Mbps) Padrão IEEE: 802.5
		c. Topologia em barramento: há uma espinha dorsal (backbone) conectando todos os computadores. Nas extremidades do backbone hás os terminadores, que sinalizam o fim da transmissão. Sendo multiponto. O meio físico de transmissão é half-duplex.
			Tipos de cabos 
				coaxial
				fibra óptica
			
			Tipos de tecnologias: 
				ethernet (10Mbps) Padrão IEEE: 802.3
				token bus (10Mbps) adrão IEEE: 802.4
				
			