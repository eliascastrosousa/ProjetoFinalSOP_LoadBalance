# ProjetoFinalSOP_LoadBalance
## Projeto da Disciplina Sistemas Operacionais + Linguagem de programação

O projeto será uma aplicação Load Balance, Teremos 5 Maquinas para fazer toda a aplicação. pensando em fazer um projeto de ponta a ponta, conectando com PHP e MariaDB.

![Alt ou título da imagem](/2021-12-16%2019_33_21-Calculadora.png)

### 1. Maquinas

1. **Maquina Gateway**
   Está Maquina ficará responsavel por compartilhar internet para as outras Web01 e Web02
2. **Maquina Web01 e Web02** 
    Responsaveis por balancear os acessos ao site. 

3. **Maquina de Operacao**
   Esta maquina será usada para manusear todas as outras 3 anteriores, pois serão instaladas em modo grafico e serão somente acessadas via ssh. 

4. **Maquina Desenvolvedor**
    Ficará responsavel por toda a parte de desenvolvimento 

### 2. Configurações da maquina e de rede

**Nesta parte lidaremos as configurações das maquinas no virtual box.**

1. **Maquina Gateway**
    Hostname: gateway
    IPv4: 192.168.0.101
    FQDN: gateway.projeto.br
    Usuario: sysadmin
    Senha: sysadmin
    Senha Root: 5y54dm1n
    <br>
   
2. **Maquina Web01 e Web02** 
    Hostname: web01 e web02
    IPv4: 192.168.0.102 e 192.168.0.103
    FQDN: web01.projeto.br e web02.projeto.br
    Usuario: sysadmin
    Senha: sysadmin
    Senha Root: 5y54dm1n
    <br>

3. **Maquina Desenvolvedor**
    Hostname: dev
    IPv4: 192.168.0.105
    FQDN: dev.projeto.br
    Usuario: sysadmin
    Senha: sysadmin
    Senha Root: 5y54dm1n
    <br>

4. **Maquina de Operacao**
    Hostname: operacao
    IPv4: 192.168.0.151
    FQDN: operacao.projeto.br
    Usuario: sysadmin
    Senha: sysadmin
    Senha Root: 5y54dm1n
    <br> 
 

## Comandos Utilizados no projeto

**su -** : Entrar como Root <br>
**ip a** : mverificar as interfaces de ip da maquina
**passwd**: mudar senha do usuario logado
**ss -nltp**: verificar se o serviço ssh existe na maquina
**system ctl start sshd**: 



