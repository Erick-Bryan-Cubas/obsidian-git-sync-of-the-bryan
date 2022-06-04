O Linux diferente do Windows que associa o arquivo a sua extensão, há maior ênfase no conteúdo do arquivo. Devido as várias distribuições, há uma extensão própria para cada gerenciador de [[pacotes]]

## Instalando o CODE:BLOCKS

1. Realize a instalação dos metacotes com o [[build-essential]]
2. Abra o arquivo de configuração _sources.list_ (no exemplo utilizamos o Nano)

````bash 
$ nano /etc/apt/sources.list
````
No arquivo, insira em quaisquer linhas o respectivo repositório:
``deb http://ftp.debian.org/debian [versão do Debian]-backports main``

3. Por fim, digite o comando de instalação:

````bash
$ apt -t [versão do Debian]-backports install codeblocks
````

## Instalando o Intellij
1. Digite o respectivo comando

````bash
$ sudo snap install intellij-idea-community --classic
````
