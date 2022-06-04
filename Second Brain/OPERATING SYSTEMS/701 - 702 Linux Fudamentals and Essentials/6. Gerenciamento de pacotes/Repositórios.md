Os repositórios são grandes centralizadores de extensões [[.deb]]. Podem obter tanto via protocolos [[http]] ou [[FTP]]. Em pesquisa atráves de browser, utilize sourcelist [programa]. 

Os repositórios globais no Debian se alocam no diretório 

```bash
cat /etc/apt/sources.list
```

São nesses arquivos, os [[espelhos de rede]], que o Debian irá buscar os requisitos de uma determinada instalação. 
Os repositórios específicos se encontram no diretório :
```bash
cd  /etc/apt/sources.list.d/
```

A sintaxe dos repositórios segue o padrão de **tipo de pacote**  **protocolo de acesso** e **endereço** de rede das extensões, a **versão** e a [[Seção de pacote]]
Caso o usuário perca o arquivo, pode encontrar o exemplo em:
```bash
cd /usr/share/doc/apt/examples/
```

Quais as diferenças?
[[apt-get]] X [[aptitude]]

Para encontrar a viabilidade do _aptitude_:
```bash
apt-cache search aptitude 
```
Nessa listagem procure por:
```bash
aptitude - terminal-based package manager 
```
Para pesquisar um pacote no _aptitude_:
```bash
aptitude searh [pacote]
```

Para instalat o _aptitude_:
```bash
apt-get -i aptitude 
```

