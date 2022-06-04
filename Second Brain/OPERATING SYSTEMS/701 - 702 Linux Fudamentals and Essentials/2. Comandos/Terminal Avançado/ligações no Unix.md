[[Ligação forte]] - nome para um arquivo
[[Ligação simbólica | Ligação fraca]] - nome de caminho 

Argumentos obrigatórios para opções longas também o são para opções curtas.
  [[--all | -a]]              
  [[--almost-all | -A]]          
  [[--author]]               
  [[--escape | -b]]      
  [[--block-size=TAM]]      
                              
  -B, --ignore-backups       não lista as entradas implícitas terminadas com ~
  -c                         com -lt: ordena por, e mostra, ctime (hora da
                               última modificação da informação de estado do
                               arquivo);
                               com -l: mostra o ctime e ordena por nome
                               demais casos: ordena por ctime, mais novos
                               primeiro
  -C                         lista as entradas em colunas
      --color[=QUANDO]       controla se usa cores para distinguir os tipos de
                               arquivo. QUANDO pode ser "never" (nunca),
                               "always" (sempre) ou "auto" (automaticamente)
  -d, --directory            lista os diretórios em si, e não seu conteúdo
  -D, --dired                gera a saída projetada para modo "dired" do Emacs
  -f                         não ordena, habilita -aU, desabilita -ls --color
  -F, --classify             anexa indicador (um dos */=>@|) às entradas
      --file-type            similar, exceto que não anexa "*"
      --format=PALAVRA       "across" -x, "commas" -m, "horizontal" -x,
                               "long" -l, "single-column" -1,
                               "verbose" -l, "vertical" -C
      --full-time            o mesmo que -l --time-style=full-iso
  -g                         o mesmo que -l, mas não lista o dono
      --group-directories-first
                             lista os diretórios antes de listar os arquivos;
                               pode ser ampliado com a opção --sort, mas o uso
                               de --sort=none (-U) desabilita o agrupamento de
                               diretórios
  -G, --no-group             em lista longa, não emite os nomes de grupo
  -h, --human-readable       com -l, e/ou -s, emite tamanhos tipo 1K 234M 2G...
      --si                   similar, mas usa potências de 1000, não de 1024
  -H, --dereference-command-line
                             segue os links simbólicos listados na linha de
                               comando
      --dereference-command-line-symlink-to-dir
                             segue todo link simbólico da linha de comando
                               que apontar para um diretório
      --hide=PADRÃO          não lista entradas implícitas que coincidam com o
                               PADRÃO em sintaxe shell (ignorado quando se usa
                               -a ou -A)
      --hyperlink[=QUANDO]   nomes de arquivos de hyperlink; QUANDO pode ser
                             "always" (padrão), "auto" ou "never"
      --indicator-style=PALAVRA
                             anexa o indicador de tipo no estilo PALAVRA
                               para os nomes das entradas:
                               "none" (nenhum, padrão), "slash" (-p),
                               "file-type" (--file-type), "classify" (-F)
  -i, --inode                emite o número de índice de cada arquivo
  -I, --ignore=PADRÃO        não lista as entradas implícitas que coincidam
                               com o PADRÃO (em sintaxe shell)
  -k, --kibibytes            por padrão, blocos de 1024 bytes para uso
                               do disco; usado apenas com -s e por totais
                               de diretório
  -l                         usa o formato de lista longa
  -L, --dereference          ao mostrar informações de um link simbólico,
                               mostra as do arquivo ao qual ele referencia,
                               e não do arquivo tipo link em si
  -m                         preenche toda a largura com uma lista de entradas
                               separadas por vírgula
  -n, --numeric-uid-gid      como -l, mas lista usuário e grupo em números ID
  -N, --literal              emite nomes de entrada sem apas
  -o                         como -l, mas não lista informações sobre o grupo
  -p, --indicator-style=slash
                             anexa o indicador / aos diretórios
  -q, --hide-control-chars   emite ? em vez de caracteres não gráficos
      --show-control-chars   emite caracteres não gráficos como são (padrão
                               a menos que o programa seja o "ls" e a saída
                               seja um terminal)
  -Q, --quote-name           coloca os nomes das entradas entre aspas duplas
      --quoting-style=PALAVRA
                             usa estilo de aspas PALAVRA para os nomes das
                               entradas:
                               literal, locale, shell, shell-always,
                               shell-escape, shell-escape-always, c, escape
                               (sobrescreve a variável QUOTING_STYLE)
  -r, --reverse              inverte a ordem na ordenação
  -R, --recursive            lista os subdiretórios recursivamente
  -s, --size                 emite o tamanho de cada arquivo, em blocos
  -S                         ordena por tamanho de arquivo (maior primeiro)
      --sort=PALAVRA         ordena por PALAVRA em vez de pelo nome: none (-U),
                               size (-S), time (-t), version (-v),
                               extension (-X)
      --time=PALAVRA         altera o padrão usando horários de modificação;
                               horário de acesso (-u): atime, access, use;
                               horário de alteração (-c): ctime, status;
                               horário de criação: birth, creation;
                             com -l, PALAVRA determina o tempo para mostrar;
                             com --sort=time, ordena por PALAVRA com o mais
                               novo primeiro
      --time-style=ESTILO_HORA formato de hora/data com -l;
                                 veja TIME_STYLE abaixo
  -t                         ordena por horário, mais novo primário;
                               veja --time
  -T, --tabsize=COLS         presume paradas de tabulação a cada COLS em vez
                               de 8
  -u                         com -lt: mostra e ordena por horário de acesso
                               com -l: mostra o horário de acesso e ordena
                               por nome; demais casos: ordena por horário
                               de acesso
  -U                         não ordena; lista na ordem do diretório
  -v                         ordem natural de números (de versão) com texto
  -w, --width=COLS           define largura saída com COLS. 0 significa
                               sem limite
  -x                         lista as entradas por linha em vez de por coluna
  -X                         ordena por ordem alfabética das extensões das
                               entradas
  -Z, --context              emite qualquer contexto de segurança de cada
                               arquivo
  -1                         lista um arquivo por linha. Com -q ou -b, evita \n
      --help     mostra esta ajuda e sai
      --version  informa a versão e sai
