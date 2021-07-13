<p align="center">
  <a href="https://onsac.com/">
    <img src="https://github.com/onsac/Scout/blob/main/Logo%20Scout.png" alt="Bootstrap logo" width="300" height="200">
  </a>
</p>

<h3 align="center">Scout</h3>

<p align="center">
  Automações e Integrações sem limitações (AIops/DEVops)
  <br>
  <a href="https://onsac.com/"><strong>Conheça mais sobre nosso serviço »</strong></a>
  </p>



## Scout

A plataforma de integração que facilita a jornada de automação e redução de custos da sua empresa.


## Procedimento de Instalação e Configuração

- [Verifica e Configura PROXY](#verifica-e-configura-proxy)
- [Instala e Configura Scout](#instala-e-configura-scout)
- [Configura Scout](#configura-scout)

## Verifica e Configura PROXY

Se sua empresa utiliza PROXY corporativo nos servidores para permitir o acesso a internet, então é pré-requisito realizar a configuração abaixo para seguir com a instalação do AIO Integrador

Deve-se editar o arquivo /etc/environment adicionando as seguintes linhas: 

```sh
http_proxy="http://USUARIO:SENHA@IP_PROXY:PORTA"
https_proxy="http://USUARIO:SENHA@IP_PROXY:PORTA"
ftp_proxy="http:///USUARIO:SENHA@IP_PROXY:PORTA"
no_proxy=localhost,127.0.0.0/8,192.168.*,10.*
```

## Instala e Configura Scout

Deploy dos componentes da solução
```sh
wget --no-cache --no-check-certificate -qO- https://raw.githubusercontent.com/onsac/aio-init/main/aio-init.sh | bash -s <Informe a Chave>
```

Pós setup
```sh
sudo su - aio
cd /aio/aiop/aio-setup
node aio-setup
```

## Configura Scout

Tela inicial – <Login> para usuários já cadastrados e <Novo usuário> para registros de novos usuários 
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%201.jpeg" alt="Tela-Scout (1)" >
</p>

<Novo usuário> para registros de novos usuários
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%202.jpeg" alt="Tela-Scout (2)" >
</p>

Procedimento de carga dos alunos 
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%203.jpeg" alt="Tela-Scout (3)" >
</p>

Procedimento de carga dos alunos:
1 – Baixar a Planilha Padrão 
2 – Selecione a planilha atualizada com os alunos
3 – Carrega a Planilha para o SCOUT
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%204.jpeg" alt="Tela-Scout (4)" >
</p>

Procedimento de carga da BNCC
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%205.jpeg" alt="Tela-Scout (5)" >
</p>
  
Procedimento de carga da BNCC:
1 – Baixar a Planilha do Portal MEC BNCC 
2 – Selecione a planilha atualizada com a sua BNCC
3 – Carrega a Planilha para o SCOUT
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%206.jpeg" alt="Tela-Scout (6)" >
</p>

Configuração das Avaliações
  
<p align="center">
     <img src="https://github.com/onsac/Scout/blob/main/Imagem%20Scout%207.jpeg" alt="Tela-Scout (7)" >
</p>
