---
kindle-sync:
  bookId: '17928'
  title: Como o Linux funciona
  author: 'Ward, Brian'
  highlightsCount: 48
---
# Como o Linux funciona
## Metadata
* Author: [[Ward, Brian]]

## Highlights
DevOps (Development and Operations, — location: [218]() ^ref-57708

---
OpenWRT, — location: [259]() ^ref-24894

---
leia o livro The Daemon, the Gnu, and the Penguin (Reed Media Services, 2008), — location: [275]() ^ref-51049

---
Ao criar um componente de software, os desenvolvedores geralmente não pensam muito na estrutura interna dos outros componentes, porém se preocupam com quais outros componentes eles podem usar e como utilizá-los. — location: [305]() ^ref-33529

---
Uma camada ou nível corresponde a uma classificação (ou agrupamento) de um componente de acordo com a posição que esse componente ocupa entre o usuário e o hardware. — location: [312]() ^ref-48551

---
hardware está na base. Ele inclui a memória, assim como uma ou mais CPUs (Central Processing Units, ou Unidades centrais de processamento) para realizar processamentos, além de ler e escrever na memória. Dispositivos como discos e interfaces de rede também fazem parte do hardware. — location: [316]() ^ref-29297

---
kernel, que é o núcleo do sistema operacional. O kernel é um software que reside na memória e diz à CPU o que ela — location: [318]() ^ref-37221

---
deve fazer. Ele administra o hardware e atua principalmente como uma interface entre esse e qualquer programa em execução. — location: [319]() ^ref-39002

---
Os processos – programas em execução administrados pelo kernel – formam coletivamente o nível mais alto do sistema, chamado de espaço de usuário (user space). (Um termo mais específico para processo é processo de usuário (user process), independentemente de um usuário interagir ou não diretamente com o processo. — location: [320]() ^ref-27956

---
Um código executando em modo kernel tem acesso irrestrito ao processador e à memória principal. — location: [325]() ^ref-22191

---
processamento científico — location: [333]() ^ref-15825

O que é processamento científico na memória  de segundo plano?

---
Toda entrada e saída dos dispositivos periféricos flui pela memória principal, também na forma de um conjunto de bits. Uma CPU é somente algo que executa operações na memória: ela lê instruções e dados da memória e escreve dados de volta nela. — location: [342]() ^ref-37420

---
Pelo fato de ser comum referir-se ao estado em termos abstratos em vez de usar os bits propriamente ditos, o termo imagem refere-se a uma organização física em particular dos bits. — location: [351]() ^ref-16417

---
tarefas do kernel consiste em separar a memória em várias subdivisões, e ele deve manter determinadas informações de estado sobre essas subdivisões o tempo todo. — location: [354]() ^ref-52807

---
• Chamadas de sistema — location: [362]() ^ref-55646

---
Operating System Concepts, 9ª edição, de Abraham Silberschatz, Peter B. Galvin e Greg Gagne (Wiley, 2012), e Modern Operating Systems, 4ª edição, de Andrew S. Tanenbaum e Herbert Bos (Prentice Hall, 2014). — location: [366]() ^ref-27367

---
O ato de um processo passar o controle da CPU para outro processo chama-se alternância de contexto (context switch). — location: [377]() ^ref-41670

---
porção de tempo – chamada de time slice (fatia de tempo) — location: [378]() ^ref-63317

---
sistema com várias CPUs, — location: [396]() ^ref-2575

---
pois o kernel não precisa ceder o controle de sua CPU corrente para permitir que um processo execute em uma CPU diferente. No entanto, para maximizar o uso de todas as CPUs disponíveis, — location: [397]() ^ref-23327

---
MMU (Memory Management Unit, — location: [409]() ^ref-2435

---
tabela de páginas (page table). — location: [416]() ^ref-13511

---
os device drivers, tradicionalmente, têm feito parte do kernel e se esforçam em apresentar uma interface uniforme aos processos de usuário para simplificar o trabalho dos desenvolvedores de software. — location: [422]() ^ref-38605

---
drivers — location: [418]() ^ref-56834

---
chamadas de sistema (ou syscalls) — location: [425]() ^ref-15648

---
fork() — location: [429]() ^ref-6405

---
exec() — location: [430]() ^ref-62455

---
Um exemplo bem simples é qualquer programa que seja executado na linha de comando, por exemplo, o comando ls para mostrar o conteúdo de um diretório. Ao digitar ls em uma janela de terminal, o shell que estiver executando na janela do terminal chamará fork() para criar uma cópia do shell e, em seguida, a nova cópia do shell chamará exec(ls) para executar ls. — location: [434]() ^ref-63931

---
chamada de sistema consiste em uma interação entre um processo e o kernel. — location: [442]() ^ref-43851

---
Os pseudodispositivos se parecem com os dispositivos para os processos de usuário, porém são puramente implementados em software. — location: [447]() ^ref-36227

---
(user space). — location: [455]() ^ref-28270

---
que os componentes na parte superior estão mais próximos do usuário — location: [463]() ^ref-14537

---
logs. — location: [472]() ^ref-10212

---
syslog — location: [473]() ^ref-28067

---
identifica os usuários por meio de identificadores numéricos simples chamados de userids. — location: [481]() ^ref-52467

---
porém não poderá interferir nos processos de outros usuários. — location: [485]() ^ref-20626

---
proprietário (owner), — location: [484]() ^ref-18419

---
o root pode terminar e alterar os processos de outros usuários, além de ler qualquer arquivo do sistema local. — location: [489]() ^ref-56069

---
superusuário (superuser). — location: [490]() ^ref-47569

---
Unix para iniciantes, além daqueles encontrados neste livro, considere a leitura de The Linux Command Line (No Starch Press, 2012), UNIX for the Impatient (Addison-Wesley Professional, 1995) e Learning the UNIX Operating System, 5ª edição (O'Reilly, 2001). — location: [517]() ^ref-29343

---
exibe o conteúdo de um ou mais arquivos. — location: [556]() ^ref-41397

---
ele faz uma concatenação ao exibir o conteúdo de mais de um arquivo. — location: [561]() ^ref-44478

---
rm -rf dir — location: [668]() ^ref-12390

---
E, acima de tudo, sempre confira o seu comando duas vezes antes de executá-lo. — location: [671]() ^ref-53738

---
mais simples dos caracteres de glob é o *, que diz ao shell para efetuar a correspondência com qualquer quantidade de caracteres arbitrários. Por exemplo, o comando a seguir exibe os arquivos do diretório corrente: — location: [674]() ^ref-31195

---
ponto de interrogação (?) – instrui o shell a efetuar a correspondência exata com um caractere arbitrário. — location: [691]() ^ref-29308

---
o shell expande os globs antes de executar os comandos.) — location: [763]() ^ref-38507

---
[[sistema de arquivos]] (filesystem) – o banco de dados de arquivos e diretórios com o qual você está acostumado a interagir no espaço de usuário. — location: [1996]() ^ref-9652

---
