                                                                                                                                                                   
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# grep --help              
Uso: grep [OPÇÃO]... PADRÕES [ARQUIVO]...
Busca por PADRÕES em cada ARQUIVO.
Exemplo: grep -i "olá, mundo" menu.h main.c
PADRÕES pode conter múltiplos padrões separados por nova-linha.

Seleção e interpretação de padrão:
  -E, --extended-regexp     PADRÕES são expressões regulares estendidas
  -F, --fixed-strings       PADRÕES são textos
  -G, --basic-regexp        PADRÕES são expressões regulares básicas
  -P, --perl-regexp         PADRÕES são expressões regulares Perl
  -e, --regexp=PADRÕES      usa PADRÕES para coincidir
  -f, --file=ARQUIVO        obtém PADRÕES contidos no ARQUIVO
  -i, --ignore-case         ignora diferenças entre maiúsculas/minúsculas nos
                              padrões e dados
      --no-ignore-case      não ignora diferença de maiusculizações (padrão)
  -w, --word-regexp         coincide só com palavras completas
  -x, --line-regexp         coincide só com linhas inteiras
  -z, --null-data           uma linha de dados termina com byte 0, e não com
                              caractere de nova linha

Miscelânea:
  -s, --no-messages         suprime mensagens de erro
  -v, --invert-match        seleciona somente linhas não coincidentes
  -V, --version             mostra informações sobre versão e sai
      --help                exibe esta ajuda e sai

Controle de saída:
  -m, --max-count=NÚM       interrompe depois de NÚM ocorrências
  -b, --byte-offset         emite a posição em bytes nas linhas de saída
  -n, --line-number         emite o número da linha nas linhas de saída
      --line-buffered       libera a saída a cada linha
  -H, --with-filename       emite o nome do arquivo nas linhas de saída
  -h, --no-filename         inibe o nome de arquivo na saída
      --label=RÓTULO        usa RÓTULO como nome de arquivo para entrada padrão
  -o, --only-matching       mostra apenas as partes não-vazias das linhas que
                              coincidem com os PADRÕES
  -q, --quiet, --silent     inibe todas as mensagens normais de saída
      --binary-files=TIPO   assume que arquivos binários são TIPO;
                             TIPO pode ser \"binary\" (binário), \"text\" (texto),
                             ou \"without-match\" (nunca coincide)
  -a, --text                equivalente a --binary-files=text
  -I                        equivalente a --binary-files=without-match
  -d, --directories=AÇÃO    como tratar diretórios;
                             AÇÃO pode ser \"read\" (ler), \"recurse\" (recursivo),
                             ou \"skip\" (ignorar)
  -D, --devices=AÇÃO        como tratar dispositivos, FIFOs e soquetes;
                             AÇÃO pode ser \"read\" (ler) ou \"skip\" (ignorar)
  -r, --recursive           equivalente a --directories=recurse
  -R, --dereference-recursive  similar, mas segue todas as ligações simbólicas
      --include=PADRÃO      busca apenas em arquivos que casam com PADRÃO
      --exclude=PADRÃO      ignora arquivos que casam com PADRÃO
      --exclude-from=ARQUI  ignora arquivos que casam com algum padrão de
                              arquivo contido em ARQUIvo
      --exclude-dir=PADRÃO  ignora diretórios que casam com PADRÃO
  -L, --files-without-match emite apenas os nomes dos ARQUIVOs sem linhas
                              selecionadas
  -l, --files-with-matches  emite apenas os nomes dos ARQUIVOs com linhas
                              selecionadas
  -c, --count               emite apenas a contagem de linhas selecionadas
                              por ARQUIVO
  -T, --initial-tab         alinha por tabulação (se necessário)
  -Z, --null                emite byte 0 depois do nome do ARQUIVO

Controle de contexto:
  -B, --before-context=NÚM  emite NÚM linhas de contexto anteriores
  -A, --after-context=NÚM   emite NÚM linhas de contexto posteriores
  -C, --context=NÚM         emite NÚM linhas de contexto de saída
  -NUM                      igual a --context=NUM
      --group-separator=SEP  imprimir SEP na linha entre correspondências com contexto
      --no-group-separator  não imprimir separador para correspondências com contexto
      --color[=QUANDO],
      --colour[=QUANDO]       usar marcadores para realçar as cadeias coincidentes;
                            QUANDO é "always", "never" ou "auto"
  -U, --binary              não eliminar caracteres CR em EOL (MSDOS/Windows)

Quando ARQUIVO é "-", lê da entrada padrão. Se ARQUIVO não é informado, lê "."
se recursivo, senão lê "-". Se há menos que dois ARQUIVOs, assume-se -h.
O estado de saída é 0 se alguma linha é selecionada, 1 em caso contrário;
se ocorrer algum erro e -q não é especificado, o estado de saída é 2.

Relate os problemas para: bug-grep@gnu.org
pagina de GNU grep: <https://www.gnu.org/software/grep/>
Ajuda geral sobre uso de software GNU: <https://www.gnu.org/gethelp/>
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# fgrep -=help                                
grep: opção inválida -- “=”
Uso: grep [OPÇÃO]... PADRÕES [ARQUIVO]...
Experimente "grep --help" para mais informações.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# fgrep --help                                                                                                                                                  2 ⨯
Uso: grep [OPÇÃO]... PADRÕES [ARQUIVO]...
Busca por PADRÕES em cada ARQUIVO.
Exemplo: grep -i "olá, mundo" menu.h main.c
PADRÕES pode conter múltiplos padrões separados por nova-linha.

Seleção e interpretação de padrão:
  -E, --extended-regexp     PADRÕES são expressões regulares estendidas
  -F, --fixed-strings       PADRÕES são textos
  -G, --basic-regexp        PADRÕES são expressões regulares básicas
  -P, --perl-regexp         PADRÕES são expressões regulares Perl
  -e, --regexp=PADRÕES      usa PADRÕES para coincidir
  -f, --file=ARQUIVO        obtém PADRÕES contidos no ARQUIVO
  -i, --ignore-case         ignora diferenças entre maiúsculas/minúsculas nos
                              padrões e dados
      --no-ignore-case      não ignora diferença de maiusculizações (padrão)
  -w, --word-regexp         coincide só com palavras completas
  -x, --line-regexp         coincide só com linhas inteiras
  -z, --null-data           uma linha de dados termina com byte 0, e não com
                              caractere de nova linha

Miscelânea:
  -s, --no-messages         suprime mensagens de erro
  -v, --invert-match        seleciona somente linhas não coincidentes
  -V, --version             mostra informações sobre versão e sai
      --help                exibe esta ajuda e sai

Controle de saída:
  -m, --max-count=NÚM       interrompe depois de NÚM ocorrências
  -b, --byte-offset         emite a posição em bytes nas linhas de saída
  -n, --line-number         emite o número da linha nas linhas de saída
      --line-buffered       libera a saída a cada linha
  -H, --with-filename       emite o nome do arquivo nas linhas de saída
  -h, --no-filename         inibe o nome de arquivo na saída
      --label=RÓTULO        usa RÓTULO como nome de arquivo para entrada padrão
  -o, --only-matching       mostra apenas as partes não-vazias das linhas que
                              coincidem com os PADRÕES
  -q, --quiet, --silent     inibe todas as mensagens normais de saída
      --binary-files=TIPO   assume que arquivos binários são TIPO;
                             TIPO pode ser \"binary\" (binário), \"text\" (texto),
                             ou \"without-match\" (nunca coincide)
  -a, --text                equivalente a --binary-files=text
  -I                        equivalente a --binary-files=without-match
  -d, --directories=AÇÃO    como tratar diretórios;
                             AÇÃO pode ser \"read\" (ler), \"recurse\" (recursivo),
                             ou \"skip\" (ignorar)
  -D, --devices=AÇÃO        como tratar dispositivos, FIFOs e soquetes;
                             AÇÃO pode ser \"read\" (ler) ou \"skip\" (ignorar)
  -r, --recursive           equivalente a --directories=recurse
  -R, --dereference-recursive  similar, mas segue todas as ligações simbólicas
      --include=PADRÃO      busca apenas em arquivos que casam com PADRÃO
      --exclude=PADRÃO      ignora arquivos que casam com PADRÃO
      --exclude-from=ARQUI  ignora arquivos que casam com algum padrão de
                              arquivo contido em ARQUIvo
      --exclude-dir=PADRÃO  ignora diretórios que casam com PADRÃO
  -L, --files-without-match emite apenas os nomes dos ARQUIVOs sem linhas
                              selecionadas
  -l, --files-with-matches  emite apenas os nomes dos ARQUIVOs com linhas
                              selecionadas
  -c, --count               emite apenas a contagem de linhas selecionadas
                              por ARQUIVO
  -T, --initial-tab         alinha por tabulação (se necessário)
  -Z, --null                emite byte 0 depois do nome do ARQUIVO

Controle de contexto:
  -B, --before-context=NÚM  emite NÚM linhas de contexto anteriores
  -A, --after-context=NÚM   emite NÚM linhas de contexto posteriores
  -C, --context=NÚM         emite NÚM linhas de contexto de saída
  -NUM                      igual a --context=NUM
      --group-separator=SEP  imprimir SEP na linha entre correspondências com contexto
      --no-group-separator  não imprimir separador para correspondências com contexto
      --color[=QUANDO],
      --colour[=QUANDO]       usar marcadores para realçar as cadeias coincidentes;
                            QUANDO é "always", "never" ou "auto"
  -U, --binary              não eliminar caracteres CR em EOL (MSDOS/Windows)

Quando ARQUIVO é "-", lê da entrada padrão. Se ARQUIVO não é informado, lê "."
se recursivo, senão lê "-". Se há menos que dois ARQUIVOs, assume-se -h.
O estado de saída é 0 se alguma linha é selecionada, 1 em caso contrário;
se ocorrer algum erro e -q não é especificado, o estado de saída é 2.

Relate os problemas para: bug-grep@gnu.org
pagina de GNU grep: <https://www.gnu.org/software/grep/>
Ajuda geral sobre uso de software GNU: <https://www.gnu.org/gethelp/>
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# egrep --help
Uso: grep [OPÇÃO]... PADRÕES [ARQUIVO]...
Busca por PADRÕES em cada ARQUIVO.
Exemplo: grep -i "olá, mundo" menu.h main.c
PADRÕES pode conter múltiplos padrões separados por nova-linha.

Seleção e interpretação de padrão:
  -E, --extended-regexp     PADRÕES são expressões regulares estendidas
  -F, --fixed-strings       PADRÕES são textos
  -G, --basic-regexp        PADRÕES são expressões regulares básicas
  -P, --perl-regexp         PADRÕES são expressões regulares Perl
  -e, --regexp=PADRÕES      usa PADRÕES para coincidir
  -f, --file=ARQUIVO        obtém PADRÕES contidos no ARQUIVO
  -i, --ignore-case         ignora diferenças entre maiúsculas/minúsculas nos
                              padrões e dados
      --no-ignore-case      não ignora diferença de maiusculizações (padrão)
  -w, --word-regexp         coincide só com palavras completas
  -x, --line-regexp         coincide só com linhas inteiras
  -z, --null-data           uma linha de dados termina com byte 0, e não com
                              caractere de nova linha

Miscelânea:
  -s, --no-messages         suprime mensagens de erro
  -v, --invert-match        seleciona somente linhas não coincidentes
  -V, --version             mostra informações sobre versão e sai
      --help                exibe esta ajuda e sai

Controle de saída:
  -m, --max-count=NÚM       interrompe depois de NÚM ocorrências
  -b, --byte-offset         emite a posição em bytes nas linhas de saída
  -n, --line-number         emite o número da linha nas linhas de saída
      --line-buffered       libera a saída a cada linha
  -H, --with-filename       emite o nome do arquivo nas linhas de saída
  -h, --no-filename         inibe o nome de arquivo na saída
      --label=RÓTULO        usa RÓTULO como nome de arquivo para entrada padrão
  -o, --only-matching       mostra apenas as partes não-vazias das linhas que
                              coincidem com os PADRÕES
  -q, --quiet, --silent     inibe todas as mensagens normais de saída
      --binary-files=TIPO   assume que arquivos binários são TIPO;
                             TIPO pode ser \"binary\" (binário), \"text\" (texto),
                             ou \"without-match\" (nunca coincide)
  -a, --text                equivalente a --binary-files=text
  -I                        equivalente a --binary-files=without-match
  -d, --directories=AÇÃO    como tratar diretórios;
                             AÇÃO pode ser \"read\" (ler), \"recurse\" (recursivo),
                             ou \"skip\" (ignorar)
  -D, --devices=AÇÃO        como tratar dispositivos, FIFOs e soquetes;
                             AÇÃO pode ser \"read\" (ler) ou \"skip\" (ignorar)
  -r, --recursive           equivalente a --directories=recurse
  -R, --dereference-recursive  similar, mas segue todas as ligações simbólicas
      --include=PADRÃO      busca apenas em arquivos que casam com PADRÃO
      --exclude=PADRÃO      ignora arquivos que casam com PADRÃO
      --exclude-from=ARQUI  ignora arquivos que casam com algum padrão de
                              arquivo contido em ARQUIvo
      --exclude-dir=PADRÃO  ignora diretórios que casam com PADRÃO
  -L, --files-without-match emite apenas os nomes dos ARQUIVOs sem linhas
                              selecionadas
  -l, --files-with-matches  emite apenas os nomes dos ARQUIVOs com linhas
                              selecionadas
  -c, --count               emite apenas a contagem de linhas selecionadas
                              por ARQUIVO
  -T, --initial-tab         alinha por tabulação (se necessário)
  -Z, --null                emite byte 0 depois do nome do ARQUIVO

Controle de contexto:
  -B, --before-context=NÚM  emite NÚM linhas de contexto anteriores
  -A, --after-context=NÚM   emite NÚM linhas de contexto posteriores
  -C, --context=NÚM         emite NÚM linhas de contexto de saída
  -NUM                      igual a --context=NUM
      --group-separator=SEP  imprimir SEP na linha entre correspondências com contexto
      --no-group-separator  não imprimir separador para correspondências com contexto
      --color[=QUANDO],
      --colour[=QUANDO]       usar marcadores para realçar as cadeias coincidentes;
                            QUANDO é "always", "never" ou "auto"
  -U, --binary              não eliminar caracteres CR em EOL (MSDOS/Windows)

Quando ARQUIVO é "-", lê da entrada padrão. Se ARQUIVO não é informado, lê "."
se recursivo, senão lê "-". Se há menos que dois ARQUIVOs, assume-se -h.
O estado de saída é 0 se alguma linha é selecionada, 1 em caso contrário;
se ocorrer algum erro e -q não é especificado, o estado de saída é 2.

Relate os problemas para: bug-grep@gnu.org
pagina de GNU grep: <https://www.gnu.org/software/grep/>
Ajuda geral sobre uso de software GNU: <https://www.gnu.org/gethelp/>
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# locate --help
Usage: plocate [OPTION]... PATTERN...

  -b, --basename         search only the file name portion of path names
  -c, --count            print number of matches instead of the matches
  -d, --database DBPATH  search for files in DBPATH
                         (default is /var/lib/plocate/plocate.db)
  -i, --ignore-case      search case-insensitively
  -l, --limit LIMIT      stop after LIMIT matches
  -0, --null             delimit matches by NUL instead of newline
  -N, --literal          do not quote filenames, even if printing to a tty
  -r, --regexp           interpret patterns as basic regexps (slow)
      --regex            interpret patterns as extended regexps (slow)
  -w, --wholename        search the entire path name (default; see -b)
      --help             print this help
      --version          print version information
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# apt install mlocate             
Lendo listas de pacotes... Pronto
Construindo árvore de dependências... Pronto
Lendo informação de estado... Pronto        
Os seguintes pacotes foram instalados automaticamente e já não são necessários:
  hddtemp liburing1 libvpx6 ruby-atomic ruby-thread-safe
Utilize 'apt autoremove' para os remover.
Os NOVOS pacotes a seguir serão instalados:
  mlocate
0 pacotes atualizados, 1 pacotes novos instalados, 0 a serem removidos e 58 não atualizados.
É preciso baixar 4.996 B de arquivos.
Depois desta operação, 15,4 kB adicionais de espaço em disco serão usados.
Obter:1 http://kali.download/kali kali-rolling/main amd64 mlocate all 1.1.14-1 [4.996 B]
Baixados 4.996 B em 3s (1.447 B/s)  
A seleccionar pacote anteriormente não seleccionado mlocate.
(Lendo banco de dados ... 335243 ficheiros e directórios actualmente instalados.)
A preparar para desempacotar .../mlocate_1.1.14-1_all.deb ...
A descompactar mlocate (1.1.14-1) ...
Configurando mlocate (1.1.14-1) ...
dpkg-statoverride: aviso: não está presente nenhum 'override'
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# update db   
Command 'update' not found, did you mean:
  command 'zupdate' from deb zutils
  command 'lupdate' from deb qtchooser
  command 'uupdate' from deb devscripts
  command 'xupdate' from deb libxml-xupdate-libxml-perl
Try: apt install <deb name>
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# updatedb                                                                                                                                                    127 ⨯
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# whereis  
whereis: not enough arguments
Try 'whereis --help' for more information.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# whereis --help                                                                                                                                                1 ⨯

Usage:
 whereis [options] [-BMS <dir>... -f] <name>

Locate the binary, source, and manual-page files for a command.

Options:
 -b         search only for binaries
 -B <dirs>  define binaries lookup path
 -m         search only for manuals and infos
 -M <dirs>  define man and info lookup path
 -s         search only for sources
 -S <dirs>  define sources lookup path
 -f         terminate <dirs> argument list
 -u         search for unusual entries
 -l         output effective lookup paths

 -h, --help     display this help
 -V, --version  display version

For more details see whereis(1).
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# apropos --help     
Uso: apropos [OPÇÃO...] PALAVRA-CHAVE...

  -d, --debug                emite mensagens de depuração
  -v, --verbose              emite mensagens de aviso detalhadas
  -e, --exact                pesquisa cada palavra-chave por correspondência
                             exata
  -r, --regex                interpreta cada palavra-chave como uma expressão
                             regular
  -w, --wildcard             a(s) palavra-chave(s) não podem conter caracteres
                             coringas
  -a, --and                  exige correspondência de todas as palavra-chaves
  -l, --long                 não corta a saída para a largura do terminal
  -C, --config-file=ARQUIVO  usa esse arquivo de configuração de usuário
  -L, --locale=LOCALIDADE    define a localidade para esta pesquisa
  -m, --systems=SISTEMA      usa páginas de manual para outros sistemas
  -M, --manpath=CAMINHO      define o caminho de pesquisa por páginas de
                             manual com CAMINHO
  -s, --sections=LISTA, --section=LISTA
                             pesquisa apenas nestas seções (separadas por
                             dois-pontos)
  -?, --help                 fornece esta lista de ajuda
      --usage                fornece uma mensagem de uso curta
  -V, --version              mostra a versão do programa

Argumentos obrigatórios ou opcionais para opções longas também o são para
quaisquer opções curtas correspondentes.

The --regex option is enabled by default.

Relate erros para cjwatson@debian.org.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# find --help 
Usage: find [-H] [-L] [-P] [-Olevel] [-D debugopts] [path...] [expression]

o caminho padrão é o diretório atual; a expressão padrão é -print
expressões podem consistir em: operadores, opções, testes e ações:
operadores (precedência decrescente; -and é implícito onde nenhum outro for fornecido):
      ( EXPR )   ! EXPR   -not EXPR   EXPR1 -a EXPR2   EXPR1 -and EXPR2
      EXPR1 -o EXPR2   EXPR1 -or EXPR2   EXPR1 , EXPR2
opções posicionais (sempre verdadeiras): -daystart -follow -regextype

opções normais (sempre verdadeiras, especificadas antes de outras expressões):
      -depth --help -maxdepth NÍVEIS -mindepth NÍVEIS -mount -noleaf
      --version -xdev -ignore_readdir_race -noignore_readdir_race
testes (N pode ser +N ou -N ou N): -amin N -anewer ARQUIVO -atime N -cmin N
      -cnewer ARQUIVO -ctime N -empty -false -fstype TIPO -gid N -group NOME
      -ilname PADRÃO -iname PADRÃO -inum N -iwholename PADRÃO -iregex PADRÃO
      -links N -lname PADRÃO -mmin N -mtime N -name PADRÃO -newer ARQUIVO
      -nouser -nogroup -path PATTERN -perm [-/]MODE -regex PATTERN
      -readable -writable -executable
      -wholename PATTERN -size N[bcwkMG] -true -type [bcdpflsD] -uid N
      -used N -user NAME -xtype [bcdpfls]      -context CONTEXTO

actions: -delete -print0 -printf FORMAT -fprintf FILE FORMAT -print 
      -fprint0 FILE -fprint FILE -ls -fls FILE -prune -quit
      -exec COMMAND ; -exec COMMAND {} + -ok COMMAND ;
      -execdir COMMAND ; -execdir COMMAND {} + -okdir COMMAND ;

Valid arguments for -D:
exec, opt, rates, search, stat, time, tree, all, help
Use '-D help' for a description of the options, or see find(1)

Please see also the documentation at http://www.gnu.org/software/findutils/.
You can report (and track progress on fixing) bugs in the "find"
program via the GNU findutils bug-reporting page at
https://savannah.gnu.org/bugs/?group=findutils or, if
you have no web access, by sending email to <bug-findutils@gnu.org>.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# find /etc/ -maxdepth 1 -name "*.conf" -type f -size -2k -atime -30
/etc/host.conf
/etc/fuse.conf
/etc/resolv.conf
/etc/ld.so.conf
/etc/updatedb.conf
/etc/nsswitch.conf
/etc/mke2fs.conf
/etc/pam.conf
/etc/logrotate.conf
/etc/e2scrub.conf
/etc/nftables.conf
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# find /etc/ -maxdepth 1 -name "*.conf" -type f -size -2k -atime -30 -exec cp {} /tmp/ \;
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# apt install zip unzip rar unrar 7zip
Lendo listas de pacotes... Pronto
Construindo árvore de dependências... Pronto
Lendo informação de estado... Pronto        
unzip is already the newest version (6.0-26).
unzip configurado para instalar manualmente.
zip is already the newest version (3.0-12).
zip configurado para instalar manualmente.
unrar is already the newest version (1:6.1.3-2).
unrar configurado para instalar manualmente.
Os seguintes pacotes foram instalados automaticamente e já não são necessários:
  hddtemp liburing1 libvpx6 ruby-atomic ruby-thread-safe
Utilize 'apt autoremove' para os remover.
Os NOVOS pacotes a seguir serão instalados:
  7zip rar
0 pacotes atualizados, 2 pacotes novos instalados, 0 a serem removidos e 58 não atualizados.
É preciso baixar 1.206 kB de arquivos.
Depois desta operação, 3.652 kB adicionais de espaço em disco serão usados.
Você quer continuar? [S/n] s
Obter:1 http://http.kali.org/kali kali-rolling/main amd64 7zip amd64 21.07+dfsg-1 [889 kB]
Obter:2 http://kali.download/kali kali-rolling/non-free amd64 rar amd64 2:5.5.0-1.1 [317 kB]
Baixados 1.206 kB em 3s (378 kB/s)
A seleccionar pacote anteriormente não seleccionado 7zip.
(Lendo banco de dados ... 335246 ficheiros e directórios actualmente instalados.)
A preparar para desempacotar .../7zip_21.07+dfsg-1_amd64.deb ...
A descompactar 7zip (21.07+dfsg-1) ...
A seleccionar pacote anteriormente não seleccionado rar.
A preparar para desempacotar .../rar_2%3a5.5.0-1.1_amd64.deb ...
A descompactar rar (2:5.5.0-1.1) ...
Configurando rar (2:5.5.0-1.1) ...
Configurando 7zip (21.07+dfsg-1) ...
A processar 'triggers' para kali-menu (2021.4.2) ...
A processar 'triggers' para man-db (2.9.4-4) ...
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# gzip --help
Usage: gzip [OPTION]... [FILE]...
Compress or uncompress FILEs (by default, compress FILES in-place).

Mandatory arguments to long options are mandatory for short options too.

  -c, --stdout      write on standard output, keep original files unchanged
  -d, --decompress  decompress
  -f, --force       force overwrite of output file and compress links
  -h, --help        give this help
  -k, --keep        keep (don't delete) input files
  -l, --list        list compressed file contents
  -L, --license     display software license
  -n, --no-name     do not save or restore the original name and timestamp
  -N, --name        save or restore the original name and timestamp
  -q, --quiet       suppress all warnings
  -r, --recursive   operate recursively on directories
      --rsyncable   make rsync-friendly archive
  -S, --suffix=SUF  use suffix SUF on compressed files
      --synchronous synchronous output (safer if system crashes, but slower)
  -t, --test        test compressed file integrity
  -v, --verbose     verbose mode
  -V, --version     display version number
  -1, --fast        compress faster
  -9, --best        compress better

With no FILE, or when FILE is -, read standard input.

Report bugs to <bug-gzip@gnu.org>.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# tar --help
Uso: tar [OPÇÃO...] [ARQUIVO]...
GNU 'tar' saves many files together into a single tape or disk archive, and can
restore individual files from the archive.

Examples:
  tar -cf archive.tar foo bar  # Create archive.tar from files foo and bar.
  tar -tvf archive.tar         # List all files in archive.tar verbosely.
  tar -xf archive.tar          # Extract all files from archive.tar.

 Modo de operação principal:
  -A, --catenate, --concatenate   anexa arquivos do tar a um arquivo-tar
  -c, --create               cria um novo arquivo-tar
      --delete               exclui do arquivo-tar (não em fitas
                             magnéticas!)
  -d, --diff, --compare      encontra diferenças entre um arquivo-tar e o
                             sistema de arquivos
  -r, --append               anexa arquivos ao final de um arquivo-tar
      --test-label           testa o rótulo de volume do arquivo-tar e sai
  -t, --list                 lista os conteúdos de um arquivo-tar
  -u, --update               anexa apenas arquivos mais novos do que a cópia
                             no arquivo-tar
  -x, --extract, --get       extrai arquivos de um arquivo-tar

 Modificadores de operação:

      --check-device         verifica números de dispositivos ao criar
                             arquivos-tar incrementais (padrão)
  -g, --listed-incremental=ARQUIVO
                             trata do novo formato GNU de backup incremental
  -G, --incremental          trata do antigo formato GNU de backup incremental
      --hole-detection=TIPO  técnica para detectar lacunas
      --ignore-failed-read   não sai com não-zero em arquivos ilegíveis
      --level=NUMERO         nível de despejo para arquivo-tar criado com
                             --listed-incremental
      --no-check-device      não verifica números de dispositivos ao criar
                             arquivos-tar incrementais
      --no-seek              arquivo-tar não é procurável
  -n, --seek                 arquivo-tar é procurável
      --occurrence[=NUMERO]  processa somente a NUMEROª ocorrência de cada
                             arquivo no arquivo-tar; esta opção é válida
                             somente em conjunção com um dos subcomandos
                             --delete, --diff, --extract ou --list e quando uma
                             lista de arquivos é dada tanto por linha de
                             comando com pela opção -T; NUMERO é 1 por
                             padrão
      --sparse-version=MAIOR[.MENOR]
                             define a versão do formato esparso a ser usado
                             (implica --sparse)
  -S, --sparse               trata arquivos esparsos eficientemente

 Seleção de nome de arquivo local:
      --add-file=ARQUIVO     adiciona ARQUIVO dado ao arquivo-tar (útil se seu
                             nome se inicia com um traço)
  -C, --directory=DIR        muda para o diretório DIR
      --exclude=PADRÃO       exclui arquivos, dados como um PADRÃO
      --exclude-backups      exclui arquivos de backup e de trava
      --exclude-caches       exclui conteúdos de diretórios contendo
                             CACHEDIR.TAG, exceto pela própria etiqueta de
                             arquivo
      --exclude-caches-all   exclui diretórios contendo CACHEDIR.TAG
      --exclude-caches-under exclui tudo sob diretórios contendo CACHEDIR.TAG
      --exclude-ignore=ARQUIVO   lê padrões de exclusão para cada diretório
                             de ARQUIVO, se ele existir
      --exclude-ignore-recursive=ARQUIVO
                             lê padrões de exclusão para cada diretório e
                             seus subdiretórios de ARQUIVO, se ele existir
      --exclude-tag=ARQUIVO  exclui conteúdo dos diretórios contendo ARQUIVO,
                             exceto o próprio ARQUIVO
      --exclude-tag-all=ARQUIVO   exclui diretórios contendo ARQUIVO
      --exclude-tag-under=ARQUIVO
                             exclui tudo sob diretórios contendo ARQUIVO
      --exclude-vcs          exclui diretórios de sistema de controle de
                             versão
      --exclude-vcs-ignores  lê padrões de exclusão de arquivos "ignore" de
                             VCS
      --no-null              desabilita o efeito da opção --null anterior
      --no-recursion         não desce pela árvore de diretórios
      --no-unquote           não remove citação de nomes de membros ou
                             arquivos de entrada
      --no-verbatim-files-from   -T trata nomes de arquivos iniciando com
                             traço como opções (padrão)
      --null                 -T lê nomes de terminação nula, implica em
                             --verbatim-files-from
      --recursion            age recursivamente na árvore de diretórios
                             (padrão)
  -T, --files-from=ARQUIVO   obtém nomes para extrair ou criar a partir de
                             ARQUIVO
      --unquote              remove citação de nomes de membros ou arquivos
                             de entrada (padrão)
      --verbatim-files-from  -T lê nomes de arquivos literalmente (sem escape
                             ou tratamento de opção)
  -X, --exclude-from=ARQUIVO exclui padrões listados em ARQUIVO

 Opções de correspondência de nome de arquivo (afeta ambos padrões de
 exclusão e inclusão):

      --anchored             padrões combinam com início do nome do arquivo
      --ignore-case          ignora maiúsculas/minúsculas
      --no-anchored          padrões combinam depois de qualquer "/" (padrão
                             para exclusão)
      --no-ignore-case       diferencia maiúsculas/minúsculas (padrão)
      --no-wildcards         casa com o conteúdo exato da string
      --no-wildcards-match-slash   coringas não combinam com "/"
      --wildcards            usam coringas (padrão para exclusão)
      --wildcards-match-slash   coringas combinam com "/" (padrão para
                             exclusão)

 Controle de sobrescrita:

      --keep-directory-symlink   preserva links simbólico existentes para
                             diretórios ao extrair
      --keep-newer-files     não substitui arquivos existentes que sejam mais
                             novos que suas cópias no arquivo-tar
  -k, --keep-old-files       não substitui arquivos existentes durante
                             extração e os trata como erros
      --no-overwrite-dir     preserva metadados de diretórios existentes
      --one-top-level[=DIR]  cria um subdiretório para evitar ter arquivos
                             extraídos soltos
      --overwrite            sobrescreve arquivos existentes durante
                             extração
      --overwrite-dir        sobrescreve metadados de diretórios existentes ao
                             extrair (padrão)
      --recursive-unlink     esvazia hierarquias antes de extrair diretório
      --remove-files         remove arquivos após adicioná-los ao arquivo-tar
                            
      --skip-old-files       não substitui arquivos existentes durante
                             extração e os ignora silenciosamente
  -U, --unlink-first         remove cada arquivo antes de extrair sobre ele
  -W, --verify               tenta verificar o arquivo-tar após escrevê-lo

 Seleção de fluxo de saída:

      --ignore-command-error ignora código de saída de filhos
      --no-ignore-command-error   trata códigos de saída non-zero de filhos
                             como erro
  -O, --to-stdout            extrai arquivos para a saída padrão
      --to-command=COMANDO   redireciona arquivos extraídos para outro
                             programa

 Tratamento de atributos de arquivo:

      --atime-preserve[=MÉTODO]   preserva tempos de acesso em arquivos
                             despejados, tanto por restaurar os tempos após
                             leitura (MÉTODO="replace"; padrão) quanto por
                             não definir os tempos em primeiro lugar
                             (MÉTODO="system")
      --clamp-mtime          define tempo somente quando o arquivo é mais novo
                             do que foi dado com --mtime
      --delay-directory-restore   atrasa definição de permissões e tempos de
                             modificação de diretórios extraídos até o fim
                             da extração
      --group=NOME           força NOME como grupo para arquivos adicionados
      --group-map=ARQUIVO    usa ARQUIVO para mapear GIDs e nomes de donos de
                             arquivos
      --mode=ALTERAÇÕES      força (simbolicamente) modo ALTERAÇÕES para
                             arquivos adicionados
      --mtime=DATA-OU-ARQUIVO   define mtime para arquivos adicionados de
                             DATA-OU-ARQUIVO
  -m, --touch                não extrai o tempo modificado do arquivo
      --no-delay-directory-restore
                             cancela o efeito da opção
                             --delay-directory-restore
      --no-same-owner        extrai arquivos como você mesmo (padrão para
                             usuários comuns)
      --no-same-permissions  aplica o umask do usuário ao extrair permissões
                             do arquivo-tar (padrão para usuários comuns)
      --numeric-owner        sempre usa números para nomes de usuário/grupo
      --owner=NOME           força NOME como dono para arquivos adicionados
      --owner-map=ARQUIVO    usa ARQUIVO para mapear UIDs e nomes de donos de
                             arquivos
  -p, --preserve-permissions, --same-permissions
                             extrai informações sobre permissões de arquivos
                             (padrão para superusuário)
      --same-owner           tenta extrair arquivos usando o mesmo dono
                             definido dentro do arquivo-tar (padrão para
                             superusuário)
      --sort=ORDEM           ordem de organização de diretório: "none"
                             (padrão), "name" ou "inode"
  -s, --preserve-order, --same-order
                             argumentos de membros são listados na mesma ordem
                             que os arquivos no arquivo-tar

 Tratamento de atributos estendidos de arquivo:

      --acls                 habilita suporte às ACLs POSIX
      --no-acls              desabilita suporte às ACLs POSIX
      --no-selinux           desabilita suporte ao contexto de SELinux
      --no-xattrs            desabilita suporte a atributos estendidos
      --selinux              habilita suporte ao contexto de SELinux
      --xattrs               habilita suporte a atributos estendidos
      --xattrs-exclude=MÁSCARA   especifica o padrão de exclusão para chaves
                             de xattr
      --xattrs-include=MÁSCARA   especifica o padrão de inclusão para chaves
                             de xattr

 Seleção e troca de dispositivo:

      --force-local          arquivo-tar é local mesmo se tiver dois pontos
  -f, --file=ARQUIVO-TAR     usa arquivo ou dispositivo ARQUIVO-TAR
  -F, --info-script=NOME, --new-volume-script=NOME
                             executa o script no final de cada fita (implica em
                             -M)
  -L, --tape-length=NUMERO   troca a fita após escrever NUMERO x 1024 bytes
  -M, --multi-volume         cria/lista/extrai arquivo-tar multivolume
      --rmt-command=COMANDO  usa COMANDO rmt dado ao invés de rmt
      --rsh-command=COMANDO  usa COMANDO remoto ao invés de rsh
      --volno-file=ARQUIVO   usa/atualiza o número do volume no ARQUIVO

 Blocagem de dispositivo:

  -b, --blocking-factor=BLOCOS   BLOCOS x 512 bytes por gravação
  -B, --read-full-records    refaz blocos na medida em que os lê (para
                             redirecionamentos de 4.2BSD)
  -i, --ignore-zeros         ignora blocos zerados no arquivo-tar (significa
                             fim do arquivo)
      --record-size=NUMERO   NUMERO de bytes por gravação, múltiplo de 512

 Seleção do formato de arquivo-tar:

  -H, --format=FORMATO       cria arquivo-tar no formato dado

 FORMATO é um dos seguintes:
    gnu                      formato GNU tar 1.13.x
    oldgnu                   formato GNU conforme tar <= 1.12
    pax                      formato POSIX 1003.1-2001 (pax)
    posix                    o mesmo que pax
    ustar                    formato POSIX 1003.1-1988 (ustar)
    v7                       formato tar V7 antigo

      --old-archive, --portability
                             equivalente a --format=v7
      --pax-option=palavra-chave[[:]=valor][,palavra-chave[[:]=valor]]...
                             controla palavras-chaves pax
      --posix                equivalente a --format=posix
  -V, --label=TEXTO          cria arquivo-tar com nome de volume TEXTO; ao
                             listar/extrair, usa TEXTO como um padrão de
                             casamento para nome de volume

 Opções de compressão:

  -a, --auto-compress        usa terminação do arquivo-tar para determinar o
                             programa compressor
  -I, --use-compress-program=PROG
                             filtra através de PROG (deve aceitar -d)
  -j, --bzip2                filtra o arquivo-tar por meio de bzip2
  -J, --xz                   filtra o arquivo-tar por meio de xz
      --lzip                 filtra o arquivo-tar por meio de lzip
      --lzma                 filtra o arquivo-tar por meio de xz
      --lzop                 filtra o arquivo-tar por meio de lzop
      --no-auto-compress     não usa terminação do arquivo-tar para
                             determinar o programa compressor
      --zstd                 filtra o arquivo-tar por meio de zstd
  -z, --gzip, --gunzip, --ungzip   filtra o arquivo-tar por meio de gzip
  -Z, --compress, --uncompress   filtra o arquivo-tar por meio de compress

 Seleção de arquivo local:

      --backup[=CONTROLE]    efetua backup antes da remoção, escolhe versão
                             CONTROLE
      --hard-dereference     segue links físicos; arquiva e despeja os
                             arquivos aos quais eles fazem referência
  -h, --dereference          segue links simbólicos; arquiva e despeja os
                             arquivos aos quais eles apontam
  -K, --starting-file=NOME-MEMBRO
                             inicia em NOME-MEMBRO membro ao ler o arquivo-tar
      --newer-mtime=DATA     compara data e hora apenas quando os dados mudarem
                            
  -N, --newer=DATA-OU-ARQUIVO, --after-date=DATA-OU-ARQUIVO
                             armazena apenas arquivos mais novos que
                             DATA-OU-ARQUIVO
      --one-file-system      permanece no sistema de arquivos local durante a
                             criação de arquivo-tar
  -P, --absolute-names       preserva "/"s iniciais nos nomes dos arquivos
      --suffix=STRING        cria backup antes da remoção, sobrescreve sufixo
                             usual ("~" a menos que sobrescrito pela variável
                             de ambiente SIMPLE_BACKUP_SUFFIX)

 Transformações de nome de arquivo:

      --strip-components=NUMERO   remove NUMERO no início de componentes de
                             nomes de arquivos na extração
      --transform=EXPRESSÃO, --xform=EXPRESSÃO
                             usa a substituição sed EXPRESSÃO para
                             transformar nomes de arquivos

 Saída informativa:

      --checkpoint[=NUMERO]  exibe mensagens de progresso a cada NUMERO-ésima
                             gravação (padrão 10)
      --checkpoint-action=AÇÃO   executa AÇÃO em cada ponto de
                             verificação
      --full-time            exibe tempo do arquivo em sua resolução máxima
      --index-file=ARQUIVO   envia saída verbosa para ARQUIVO
  -l, --check-links          exibe uma mensagem se nem todos links forem
                             arquivados
      --no-quote-chars=STRING   desabilita citação para caracteres de STRING
      --quote-chars=STRING   adicionalmente, cita caracteres de STRING
      --quoting-style=ESTILO define o estilo de citação de nome; veja abaixo
                             por valores válidos para ESTILO
  -R, --block-number         mostra número de bloco dentro de arquivo-tar com
                             cada mensagem
      --show-defaults        mostra padrões do tar
      --show-omitted-dirs    ao listar ou extrair, lista cada diretório que
                             não casa com os critérios de pesquisa
      --show-snapshot-field-ranges
                             mostra intervalos válidos para campos de arquivo
                             instantâneo
      --show-transformed-names, --show-stored-names
                             mostra nomes de arquivo ou arquivo-tar após
                             transformação
      --totals[=SINAL]       exibe bytes totais após processar o arquivo-tar;
                             com um argumento - emite bytes totais quando esse
                             SINAL for entregue; Sinais permitidos são:
                             SIGHUP, SIGQUIT, SIGINT, SIGUSR1 e SIGUSR2; os
                             nomes sem o prefixo SIG também são aceitos
      --utc                  exibe tempos de modificação de arquivo em UTC
  -v, --verbose              lista verbosamente os arquivos processados
      --warning=PALAVRA-CHAVE   controle de aviso
  -w, --interactive, --confirmation
                             solicita confirmação para cada ação

 Opções de compatibilidade:

  -o                         ao criar, mesmo que --old-archive; ao extrair,
                             mesmo que --no-same-owner

 Outras opções:

  -?, --help                 fornece esta lista de ajuda
      --restrict             desabilita o uso de algumas opções
                             potencialmente nocivas
      --usage                fornece uma mensagem de uso curta
      --version              mostra a versão do programa

Argumentos obrigatórios ou opcionais para opções longas também o são para
quaisquer opções curtas correspondentes.

The backup suffix is '~', unless set with --suffix or SIMPLE_BACKUP_SUFFIX.
The version control may be set with --backup or VERSION_CONTROL, values are:

  none, off       never make backups
  t, numbered     make numbered backups
  nil, existing   numbered if numbered backups exist, simple otherwise
  never, simple   always make simple backups

Argumentos válidos para a opção --quoting-style são:

  literal
  shell
  shell-always
  shell-escape
  shell-escape-always
  c
  c-maybe
  escape
  locale
  clocale

*Esse* tar utiliza como padrão:
--format=gnu -f- -b20 --quoting-style=escape --rmt-command=/usr/sbin/rmt
--rsh-command=/usr/bin/rsh
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# bzip2 --help
bzip2, a block-sorting file compressor.  Version 1.0.8, 13-Jul-2019.

   usage: bzip2 [flags and input files in any order]

   -h --help           print this message
   -d --decompress     force decompression
   -z --compress       force compression
   -k --keep           keep (don't delete) input files
   -f --force          overwrite existing output files
   -t --test           test compressed file integrity
   -c --stdout         output to standard out
   -q --quiet          suppress noncritical error messages
   -v --verbose        be verbose (a 2nd -v gives more)
   -L --license        display software version & license
   -V --version        display software version & license
   -s --small          use less memory (at most 2500k)
   -1 .. -9            set block size to 100k .. 900k
   --fast              alias for -1
   --best              alias for -9

   If invoked as `bzip2', default action is to compress.
              as `bunzip2',  default action is to decompress.
              as `bzcat', default action is to decompress to stdout.

   If no file names are given, bzip2 compresses or decompresses
   from standard input to standard output.  You can combine
   short flags, so `-v -4' means the same as -v4 or -4v, &c.

                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# apt install pbzip2                  
Lendo listas de pacotes... Pronto
Construindo árvore de dependências... Pronto
Lendo informação de estado... Pronto        
Os seguintes pacotes foram instalados automaticamente e já não são necessários:
  hddtemp liburing1 libvpx6 ruby-atomic ruby-thread-safe
Utilize 'apt autoremove' para os remover.
Os NOVOS pacotes a seguir serão instalados:
  pbzip2
0 pacotes atualizados, 1 pacotes novos instalados, 0 a serem removidos e 58 não atualizados.
É preciso baixar 44,9 kB de arquivos.
Depois desta operação, 104 kB adicionais de espaço em disco serão usados.
Obter:1 http://kali.download/kali kali-rolling/main amd64 pbzip2 amd64 1.1.13-1 [44,9 kB]
Baixados 44,9 kB em 1s (63,4 kB/s)
A seleccionar pacote anteriormente não seleccionado pbzip2.
(Lendo banco de dados ... 335272 ficheiros e directórios actualmente instalados.)
A preparar para desempacotar .../pbzip2_1.1.13-1_amd64.deb ...
A descompactar pbzip2 (1.1.13-1) ...
Configurando pbzip2 (1.1.13-1) ...
A processar 'triggers' para man-db (2.9.4-4) ...
A processar 'triggers' para kali-menu (2021.4.2) ...
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# pbzip2 --help
Parallel BZIP2 v1.1.13 [Dec 18, 2015]
By: Jeff Gilchrist [http://compression.ca]
Major contributions: Yavor Nikolov [http://javornikolov.wordpress.com]
Uses libbzip2 by Julian Seward

Usage: pbzip2 [-1 .. -9] [-b#cdfhklm#p#qrS#tVz] <filename> <filename2> <filenameN>
 -1 .. -9        set BWT block size to 100k .. 900k (default 900k)
 -b#             Block size in 100k steps (default 9 = 900k)
 -c,--stdout     Output to standard out (stdout)
 -d,--decompress Decompress file
 -f,--force      Overwrite existing output file
 -h,--help       Print this help message
 -k,--keep       Keep input file, don't delete
 -l,--loadavg    Load average determines max number processors to use
 -m#             Maximum memory usage in 1MB steps (default 100 = 100MB)
 -p#             Number of processors to use (default: autodetect [2])
 -q,--quiet      Quiet mode (default)
 -r,--read       Read entire input file into RAM and split between processors
 -S#             Child thread stack size in 1KB steps (default stack size if unspecified)
 -t,--test       Test compressed file integrity
 -v,--verbose    Verbose mode
 -V,--version    Display version info for pbzip2 then exit
 -z,--compress   Compress file (default)
 --ignore-trailing-garbage=# Ignore trailing garbage flag (1 - ignored; 0 - forbidden)

If no file names are given, pbzip2 compresses or decompresses from standard input to standard output.

Example: pbzip2 -b15vk myfile.tar
Example: pbzip2 -p4 -r -5 myfile.tar second*.txt
Example: tar cf myfile.tar.bz2 --use-compress-prog=pbzip2 dir_to_compress/
Example: pbzip2 -d -m500 myfile.tar.bz2
Example: pbzip2 -dc myfile.tar.bz2 | tar x
Example: pbzip2 -c < myfile.txt > myfile.txt.bz2 

                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# useradd --help                                                                                                                                              255 ⨯
Uso: useradd [opções] LOGIN
     useradd -D
     useradd -D [opções]

Opções:
      --badnames                do not check for bad names
  -b, --base-dir BASE_DIR       diretório base para o diretório pessoal da
                                nova conta
      --btrfs-subvolume-home    use BTRFS subvolume for home directory
  -c, --comment COMENTÁRIO      campo GECOS da nova conta
  -d, --home-dir DIR_PESSOAL    diretório pessoal da nova conta
  -D, --defaults                exibe ou altera configuração padrão do useradd
  -e, --expiredate DATA_DE_EXPIRAÇÃO  data de expiração da nova conta
  -f, --inactive INATIVO        período de inatividade de senha da nova conta
  -g, --gid GRUPO               nome ou ID do grupo primário da nova
                                conta
  -G, --groups GRUPOS           lista de grupos complementares da nova
                                conta
  -h, --help                    mostrar esta mensagem de ajuda e sair
  -k, --skel SKEL_DIR           use este diretório esqueleto (skeleton) alternativo
  -K, --key CHAVE=VALOR         sobreescreve os padrões de /etc/login.defs
  -l, --no-log-init             não adiciona o usuário aos bancos de dados
                                lastlog e faillog
  -m, --create-home             cria o diretório pessoal do usuário
  -M, --no-create-home          não cria o diretório pessoal do usuário
  -N, --no-user-group           não cria um grupo com o mesmo nome do usuário
  -o, --non-unique              permite criar usuários com UID duplicado
                                (não-único)
  -p, --password SENHA          senha criptografada da nova conta
  -r, --system                  cria uma conta de sistema
  -R, --root CHROOT_DIR         directório para onde fazer chroot
  -P, --prefix PREFIX_DIR       prefix directory where are located the /etc/* files
  -s, --shell SHELL             shell de login da nova conta
  -u, --uid UID                 ID de usuário da nova conta
  -U, --user-group              cria um grupo com o mesmo nome do usuário
  -Z, --selinux-user USUÁRIO_SE  usa um USUÁRIO_SE específico para o mapeamento de
                                 usuário SELinux

                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# userdel --help
Uso: userdel [opções] LOGIN

Opções:
  -f, --force                   força remoção dos arquivos,
                                mesmo se não forem do usuário
  -h, --help                    mostrar esta mensagem de ajuda e sair
  -r, --remove                  remove o diretório pessoal e spool de mensagens
  -R, --root CHROOT_DIR         directório para onde fazer chroot
  -P, --prefix PREFIX_DIR       prefix directory where are located the /etc/* files
  -Z, --selinux-user            remover qualquer mapeamento de utilizador SELinux para o utilizador

                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# useradd -c "Usuário Aprendiz" -d /home/aprendiz -g 100 -m -N -s /bin/zsh -u 1001 aprendiz
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# getent passwd            
root:x:0:0:root:/root:/usr/bin/zsh
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-network:x:101:102:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:102:103:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
mysql:x:103:110:MySQL Server,,,:/nonexistent:/bin/false
tss:x:104:111:TPM software stack,,,:/var/lib/tpm:/bin/false
strongswan:x:105:65534::/var/lib/strongswan:/usr/sbin/nologin
systemd-timesync:x:106:113:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
uuidd:x:107:114::/run/uuidd:/usr/sbin/nologin
redsocks:x:108:115::/var/run/redsocks:/usr/sbin/nologin
rwhod:x:109:65534::/var/spool/rwho:/usr/sbin/nologin
iodine:x:110:65534::/run/iodine:/usr/sbin/nologin
messagebus:x:111:116::/nonexistent:/usr/sbin/nologin
miredo:x:112:65534::/var/run/miredo:/usr/sbin/nologin
_rpc:x:113:65534::/run/rpcbind:/usr/sbin/nologin
usbmux:x:114:46:usbmux daemon,,,:/var/lib/usbmux:/usr/sbin/nologin
tcpdump:x:115:122::/nonexistent:/usr/sbin/nologin
rtkit:x:116:124:RealtimeKit,,,:/proc:/usr/sbin/nologin
sshd:x:117:65534::/run/sshd:/usr/sbin/nologin
xrdp:x:118:125::/run/xrdp:/usr/sbin/nologin
dnsmasq:x:119:65534:dnsmasq,,,:/var/lib/misc:/usr/sbin/nologin
statd:x:120:65534::/var/lib/nfs:/usr/sbin/nologin
avahi:x:121:129:Avahi mDNS daemon,,,:/run/avahi-daemon:/usr/sbin/nologin
stunnel4:x:122:130::/var/run/stunnel4:/usr/sbin/nologin
Debian-snmp:x:123:131::/var/lib/snmp:/bin/false
speech-dispatcher:x:124:29:Speech Dispatcher,,,:/run/speech-dispatcher:/bin/false
sslh:x:125:132::/nonexistent:/usr/sbin/nologin
postgres:x:126:133:PostgreSQL administrator,,,:/var/lib/postgresql:/bin/bash
nm-openvpn:x:127:134:NetworkManager OpenVPN,,,:/var/lib/openvpn/chroot:/usr/sbin/nologin
nm-openconnect:x:128:135:NetworkManager OpenConnect plugin,,,:/var/lib/NetworkManager:/usr/sbin/nologin
pulse:x:129:136:PulseAudio daemon,,,:/run/pulse:/usr/sbin/nologin
saned:x:130:139::/var/lib/saned:/usr/sbin/nologin
inetsim:x:131:141::/var/lib/inetsim:/usr/sbin/nologin
lightdm:x:132:142:Light Display Manager:/var/lib/lightdm:/bin/false
colord:x:133:143:colord colour management daemon,,,:/var/lib/colord:/usr/sbin/nologin
geoclue:x:134:144::/var/lib/geoclue:/usr/sbin/nologin
king-phisher:x:135:145::/var/lib/king-phisher:/usr/sbin/nologin
bryan-kali:x:1000:1000:bryan-kali,,,:/home/bryan-kali:/usr/bin/zsh
systemd-coredump:x:999:999:systemd Core Dumper:/:/usr/sbin/nologin
_flatpak:x:136:147:Flatpak system-wide installation helper,,,:/nonexistent:/usr/sbin/nologin
aprendiz:x:1001:100:Usuário Aprendiz:/home/aprendiz:/bin/zsh
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# passwd aprendiz 
Nova senha: 
Redigite a nova senha: 
passwd: senha atualizada com sucesso
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# getent --help 
Uso: getent [OPÇÃO...] base_de_dados [chave ...]
Obtém registros de banco de dados administrativo.

  -i, --no-idn               desabilita codificação de IDN
  -s, --service=CONFIG       Serviço de configuração a ser usado
  -?, --help                 Retorna este arquivo de ajuda
      --usage                Retorna uma mensagem de uso curta
  -V, --version              Mostra versão do programa

Parâmetros obrigatórios ou opcionais para opções longas são também
obrigatórios ou opcionais para qualquer opção curta correspondente.

Há suporte aos seguintes bancos de dados:
ahosts ahostsv4 ahostsv6 aliases ethers group gshadow hosts initgroups
netgroup networks passwd protocols rpc services shadow

Para instruções sobre como relatar erros, por favor veja:
<http://www.debian.org/Bugs/>.
                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# usermod --help                                                                           
Uso: usermod [opções] LOGIN

Opções:
  -b, --badnames                allow bad names
  -c, --comment COMENTÁRIO      novo valor do campo GECOS
  -d, --home DIR_PESSOAL        novo diretório de login para a nova conta de
                                usuário
  -e, --expiredate DATA_EXPIRA  define data de expiração de conta para
                                DATA_EXPIRA
  -f, --inactive INATIVO        define inatividade de senha após expiração
                                para INATIVO
  -g, --gid GRUPO               forçar usar GRUPO como novo grupo primário
  -G, --groups GRUPOS           nova lista de GRUPOS suplementares
  -a, --append                  anexa o usuário para os GRUPOS suplementares
                                mencionados pela opção -G sem remove-lo de
                                outros grupos
  -h, --help                    mostrar esta mensagem de ajuda e sair
  -l, --login LOGIN             novo valor do nome de login
  -L, --lock                    trava a conta de usuário
  -m, --move-home               move o conteúdo do diretório pessoal para
                                a novo localização (use somente com -d)
  -o, --non-unique              permitir usar UID duplicados (não-únicos)
  -p, --password SENHA          usar senha criptografada para a nova senha
  -R, --root CHROOT_DIR         directório para onde fazer chroot
  -P, --prefix PREFIX_DIR       prefix directory where are located the /etc/* files
  -s, --shell SHELL             novo shell de login para a conta de usuário
  -u, --uid UID                 novo UID para a conta de usuário
  -U, --unlock                  destravar a conta de usuário
  -v, --add-subuids FIRST-LAST  add range of subordinate uids
  -V, --del-subuids FIRST-LAST  remove range of subordinate uids
  -w, --add-subgids FIRST-LAST  add range of subordinate gids
  -W, --del-subgids FIRST-LAST  remove range of subordinate gids
  -Z, --selinux-user SEUSER     novo mapeamento de utilizador SELinux para a conta do utilizador

                                                                                                                                                                      
┌──(root💀kaliofthebryan)-[~/Downloads]
└─# userdel --help
Uso: userdel [opções] LOGIN

Opções:
  -f, --force                   força remoção dos arquivos,
                                mesmo se não forem do usuário
  -h, --help                    mostrar esta mensagem de ajuda e sair
  -r, --remove                  remove o diretório pessoal e spool de mensagens
  -R, --root CHROOT_DIR         directório para onde fazer chroot
  -P, --prefix PREFIX_DIR       prefix directory where are located the /etc/* files
  -Z, --selinux-user            remover qualquer mapeamento de utilizador SELinux para o utilizador
