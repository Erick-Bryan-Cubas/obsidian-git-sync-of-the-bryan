As diferenças para o [[apt-get]] são minímas, ambos procuram por atualizações, instalam e organizam os arquivos em seus respectivos diretórios. No entanto, o **aptitude** se sobressai por ser _flexível_. 
O aptitude possui interface dentro do terminal.
Algumas observações sobre comandos de execução:
[[aptitude install htop -d -f -s -u -y]]
O programa _htop_ foi tomado como exemplo. 

Para atualizar os pacotes
[[aptitude upgrade]] ou [[aptitude safe-upgrade]]

Para atualizar a lista de repositórios: 
[[aptitude update]]

Para remover o pacote e quaisquer lixos do programa (normalmente arquivos de configuração), use [[aptitude remove [programa] --purge ]]


Teste a instalação do _figlet_ com o aptitude
```bash
$ aptitude -i figlet
```

Para limpar os arquivos: [[aptitude clean]].