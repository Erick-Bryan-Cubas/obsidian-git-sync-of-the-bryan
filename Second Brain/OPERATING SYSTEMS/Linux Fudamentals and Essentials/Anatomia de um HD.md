Dispositivo eletromecânico usado como principal memória secundária dos computadores. Os dados são armazenados de forma não-volátil (informações não são perdidas quando o computador é desligado). As controladoras são necessárias para intermediar o diálogo entre o HD e o computador. 
Tipos de controladoras: IDE (Parallel ATA e Serial ATA), SCSI, Fibre channel e SAS. 

## Parte interna do disco rígido
1. Pratos: 
		Discos de metal cobertos por material  magnetizável;
		Giram de 90 a 250 rotações por segundo;
		Duas faces;
2. Cabeças de leitura e gravação: 
		Eletroímã na ponta do braço articulado (comando dado atuador) magnetiza os setores, gravando ou lendo dados; 
		
## Trilhas, setores e densidade de gravação 
Cada prato tem duas faces e cada face possui várias trilhas. As trilhas são círculos concêntricos, que começam no meio e vão até a borda. Cada trilha é dividida em 64 setores. A densidade de gravação é a quantidade de setores por centímetro quadrado de mídia (no caso, as faces). 
	Os HDs atuais tem uma densidade altíssima, permitindo ter até mais de um Terabyte por face do HD. 
	
## Partição 
Divisão lógica do disco rígido. O disco pode ser dividido em diversas partes, de acordo com as suas necessidades. Existem dois sistemas de particionamento para IBM-PC: 
	**MS-DOS**: mais antigo e mais , trabalha com partições primárias (até 4), partições estendidas e unidades lógicas. Funcionamento limitado em HD de até 2Tb. 
			O windows deve ser instalado em partições primárias. O Linux possibilita a instalação em partições estendidas. 
	**GPT**: mais novo, aceita HDs de mais de 2 Tb e apenas usa partições primárias (até 127)

## MBR
Master Boot Record. Setor de 512 bytes, no início do disco rígido. Contém código executável para carregar o sistema operacional instalado (boot loader)
		Gerenciadores de boot, como NTLDR, LILO, GRUB e outros, gravam pontos de chamada para a sua execução, e assim é possível ter mais de um sistema operacional instalado, bastando escolher no ato da inicialização. 
Guarda a tabela de partições do disco rígido.

## UEFI 
Unified Extensible Firmware Interface. Originalmente feita pela Intel (EFI), atualmente pertence a um consórcio , o UEFI Forum. Objetivo: substituir a BIOS dos computadores padrão IBM-PC. 
%% A BIOS não é utilizada mais %%
O UEFI permite diagnósticos remotos e reparações de computadores, mesmo sem outro sistema operacional instalado. 

## GRUB
Grand Unified Bootloader. Gerenciador de boot  adotado pelo GNU/Linux. Utiliza dois estágios, um em MBR. O outro, no diretório /boot do Linux. As configurações devem ser feitas no arquivo /etc/default/grub. Para gerar o arquivo de configuração, requer o comando update-grub. 
	GRUB_DEFAULT=x - Opção padrão (x) no menu do GRUB (0-x). 
	GRUB_TIMEOUT=x - Tempo que o grub aguardará até o usuário escolher a opção. Se não escolher, será a opção marcada no GRUB_DEFAULT. 
	GRUB_CMDLINE_LINUX="" - Campo reservado para opções de inicialização, entre elas: quiet (menos mensagens na inicialização); splash (uso de um tema para a inicialização), entre outros. 
	
	
	%% Normalmente na instalação do SO Windows seguida do Linux, o Grub é removido e regravado o MBR. A recuperação é possível por meio de ferramentas externas, tais como SGD (Super GRUB Disk), ou manualmente: Inicia-se a máquina com um Linux em LiveCD; monta-se a partição principal (mount/devesda1/mnt) e regrava-se o GRUB com o comando grub-install (grub-install --recheck --root-directory=/mnt/dev/sda)%%
	
