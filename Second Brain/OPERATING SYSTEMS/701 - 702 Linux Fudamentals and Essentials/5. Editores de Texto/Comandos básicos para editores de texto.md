Entre os principais edidotores de textos podemos citar: 
**vi** - editor de texto baseado em terminal
**vim** - editor de texto semelhante ao **vi** no entanto com melhoramentos. 
**nano** - editor de texto padrão do [[Debian]]


# nano

[[Nano]] é o editor de textos padrão do Debian, tem como principais atalhos: 
Ctrl + R : abre aquivos ou insere determinadas informações de outro arquivo;
Ctrl + X : fecha o arquivo atual e encerra o nano;
Ctrl + O : salva o arquivo	
Ctrl + K : recorta a linha 
Ctrl + ~ : copia a linha atual
Ctrl + U : cola a linha recorta e/ou copiada. 
Ctrl + Y : sobe uma página;
Ctrl + v : desce uma página; 
Alt + : avança até a primeira linha do arquivo;
Alt /: avança para última linha;
Ctrl + A: move o cursor para o início da linha;
Ctrl + E: move o cursor para o final da linha;
Ctrl + C: apresenta informações referentes a posição do cursor 
Ctrl + G: ajuda sobre comandos 
Ctrl +  T: to speel, se instalado ativa o corretor ortográfico. 
Alt + >: movimenta entre os vários arquivos abertos.




# vim
[[VIM]] é sucessor do VI, VI Improved. Sendo um dos editores de texto mais utilizados atualamente. 



**vim [opções] [arquivo]**

## Descrição

Este utilitário é um editor de textos e é uma versão melhorada do antigo _vi_ (_Vi IMproved_).  

## Algumas opções do comando

-   **-b** : permite editar arquivo binário.
-   **-h** : exibe opções do aplicativo.
-   **+n** : inicializa o cursor na _n_-ésima linha.
-   **-r** : recupera a última versão do arquivo (o arquivo estava sendo editado quando o _vim_ foi encerrado de forma não normal, por exemplo, devido a falta de energia elétrica).
-   **-R** : abre arquivo apenas para leitura.

## Formas de Trabalho  

-   O _vim_ possui três formas de trabalho: modo de linha, modo de edição e modo de comandos. A mudança de um modo para outro modo é feita através do uso da tecla Esc.
-   Após o arquivo ser aberto pelo _vim_, o modo de comandos é ativado. No _modo de comandos_, as teclas digitadas pelo usuário são interpretadas pelo _vim_ como ações a serem executadas dentro do arquivo aberto. No _modo de edição_, as teclas digitadas pelo usuário são ecoadas na tela. Para entrar neste modo, pode-se digitar, por exemplo, “a” (adicionar), “i” (incluir),etc. No _modo de linha_, o usuário define ações a serem executadas no arquivo como um todo (por exemplo, salvar, substituir caracteres, sair do aplicativo, etc). Para entrar neste modo, deve-se digitar “:”.

## Modo de comandos

-   **0** : mover o cursor para o início da linha em que o cursor está posicionado.
-   **a** : inserir texto após a posição atual do cursor.
-   **A** : inserir texto no final da linha atual.
-   **dd** : deletar linha atual.
-   **[n]+dd** : deletar _n_ linhas a partir da linha atual.
-   **G** : ir para o fim do arquivo.
-   **[n]+G** : ir para a _n_-ésima linha do arquivo.
-   **h** : voltar um caractere.
-   **H** : ir para a primeira linha exibida na tela atual.
-   **i** : inserir texto a partir da posição atual do cursor.
-   **I** : inserir texto no início da linha atual.
-   **j** : descer uma linha.
-   **J** : juntar a linha atual com a linha seguinte.
-   **[n]+J** : juntar _n_ linhas consecutivas a partir da linha atual.
-   **k** : subir uma linha.
-   **l** : avançar um caractere.
-   **L** : ir para a última linha exibida na tela atual.
-   **n** : procurar, a partir da posição atual do cursor, a próxima ocorrência do texto definido no último comando **/**.
-   **N** : procurar, a partir da posição atual do cursor e indo em direção ao início do arquivo, a próxima ocorrência do texto definido no último comando **/**.
-   **o** : inserir uma linha em branco após a linha atual.
-   **O** : inserir uma linha em branco acima da linha atual.
-   **p** : inserir linhas copiadas após a linha atual.
-   **P** : inserir linhas copiadas antes da linha atual.
-   **r** : substituir o caractere atual.
-   **R** : substituir um conjunto de caracteres.
-   **s** : deletar o caractere atual e inserir texto.
-   **S** : apagar linha e inserir novo texto na linha.
-   **u** : desfazer a última alteração feita no texto e ainda não desfeita.
-   **U** : desfazer a última alteração feita no texto.
-   **x** : apagar caractere onde o cursor está posicionado.
-   **$** : mover o cursor para o fim da linha em que o cursor está posicionado.
-   **[n]+y** : copiar _n_ linhas a partir da linha atual.
-   **yy** : copiar a linha atual.
-   **[n]+Y** : copiar _n_ linhas a partir da linha atual.
-   **YY** : copiar a linha atual.
-   **CTRL+B** : voltar uma página.
-   **CTRL+F** : avançar uma página.
-   **F1** : exibir tela de ajuda.
-   **[n]+ENTER** : ir para _n_ linhas abaixo da linha atual.
-   **[n]+.** : repetir o último comando que alterou o texto _n_ vezes a partir da posição atual do cursor.
-   **[n]+~+ENTER** : inverter a caixa (_case_) dos _n_ caracteres seguintes ao cursor.
-   **/texto** : procurar pela primeira ocorrência do texto especificado a partir da posição atual do cursor.

## Modo de linha

-   **:r arquivo** : incluir arquivo a partir da linha atual do cursor.
-   **:q+ENTER** : sair da tela de ajuda.
-   **:q!** : sair do _vim_ sem salvar as alterações.
-   **:w arquivo** : salvar arquivo com o nome especificado.
-   **:wq** : sair do _vim_ salvando as alterações.
-   **:X** : criptografa o arquivo.

## Observações

-   O Ubuntu o _vim_ é instalado por padrão e renomeado para _vi._
-   Para visualizar um arquivo binário no modo hexadecimal, abra o arquivo com _vim_ e digite:


:set nu    ou :set number 
:syntax on 
:set ic 
:set hlsearch 
:set background=dark 


