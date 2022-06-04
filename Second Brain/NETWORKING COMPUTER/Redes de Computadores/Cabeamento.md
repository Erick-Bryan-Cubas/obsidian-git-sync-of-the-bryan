As mídias de transmissão, ou meios. Mídia = meios. 
A tipologia de mídia é subdividida em:

	**Meios guiados**, que incluem: 
		a. Par trançado: os cabos de par trançado são organizados de forma entrelaçada para evitar o efeito de cancelamento (carga positiva permanece com a negativa). 
		Os cabos de par trançado se subdividem em UTP e STP: UTP condiz com o sem blindagem (Unshielded) e o STP, o blindado (shielded). TP = Twisted Pair. 	
			Quanto a blindagem do STP, são dividos em FTP, onde há uma blindagem envolta de todos os pares. e o SCTP, em que há blindagem entorno de cada par  e entorno de todos os pares. 
			![[Pasted image 20220301212406.png]]
			
		Os padrões de cores dos filamentos do cabo par trançado são TIA/EIA 568A e TIA/EIA 568B 
		No padrão Fast-Ethernet apenas os filamentos 1 (568A= verde e branco/ 568B=branco e laranja), 2 (568A= verde/ 568B= laranja), 3(568A=laranja e branco/568B=laranja e verde) e 6(568A=laranja/568B=verde) são utilizados. 
		
		Os cabos são ainda classificados em cabo direto e cabo crossover. 
		Cabo direto: utilizados quando interliga equipamentos diferentes. 
		Origem: 568A Final: 568A
		Origem: 568B Final: 568B
		Cabo crossover: empregado em equipamentos que utilizam os mesmos pinos para realizar o recebimento de dados. 
		Origem: 568A Final: 568B, ou vice-versa. Se for de forma direta não haverá comunicação. 
		![[Pasted image 20220301223141.png]]
		
		
		![[Pasted image 20220301223434.png]]
		
		Base e Broad são as formas que os dados são enviados 
		Baseband: 1 canal de transmissão (1 frequência). Transmissão digital (o e 1). Empregada em curtas distâncias. 
		Broadband: transmissão analógica. Utiliza vários canais. Empregada em longas distâncias. 
		
		ethernet - 10Mbps - requer 1 par de filamentos
		fast-ethernet - 100Mbps - requer 2 pares de filamentos 
		gigabit ethernet - 1000Mbps - requer 4 pares de filamentos 
		10 gigabit ethernet - 10.000Mbps - requer 4 pares de filamentos 
		
		
		
		Mb - taxa de velocidade 
		MB - taxa de armazenamento
		T - Twisted pair
		Tx - fullduplex
		t4 - utiliza os 4 pares de filamentos para atingir 100Mbps
		fl - fiber link 
		fx - fiber extend 
		lx - long extend 
		sx - short extend 
		lr - long range 
		
		
		
		Os filamentos 1 e 2 realizam os envios de dados. 1=Tx positivo 2= tx negativo
		Os filamentos 3 e 6 realizam os recebimentos de dados. 3=Rx positivo, 6=Rx negativo

		
		
		
		
		
		
		b. Coaxial: transmissão de 10Mbps
			Coaxial grosso: 10 base 5/ thick coax ou thick net. Requer um ==transceptor ou transceiver== para conectar em hosts. Tranceptores em gerais são os conversores de mídias. No caso do coaxial grosso, o transceptor é constituído do Vampiro (conector com dois dentes que perfura o cabo coaxial) e AUI que conecta na máquina e finaliza o processo de conversão de mídia para a placa de rede do PC. 
			Coaxial fino: 10 base 2/ thin coax ou thin net. Os transceptores do coaxial fino são: BNC, BNC-T e Terminador. 
		c. Fibra óptica: as fibras ópticas se subdividem em:
			Fibra Multimodo: vários feixes de luzes (led) sendo transmitidos por meio do cabo. 
			Fibra Monomodo: um único deixe de luz (led) transmitido por meio do cabo. 
			
		Os feixes da fibra podem ser refletidos ou sofrerem refração. O índice degrau condiz com a refração da fibra de forma constante, sem variações. O índice gradual de refração condiz com alteração com o tempo decorrido. 
		Conectores utilizados pela fibra óptica: MIC (o MIC (Medium Interface Connector) usado em redes FDDI, trabalhamos com conectores para fibras ópticas, cabos UTP e fios telefônicos)); SMA, LC, SC, MT, ST, RJ...
	
	**Meios não-guiados**:
	 	a. Wi-Fi
		b. Bluetooth 
		c. NFC
		d. Wi-Fi direct
