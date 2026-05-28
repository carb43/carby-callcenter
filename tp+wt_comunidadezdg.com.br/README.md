===================================================
##                                              ##
##   █████████      ███████         █████████   ##
##         ███      ███    ██       ███         ##
##       ███        ███    ███      ███         ##
##     ███          ███    ███      ███  ████   ##
##   ███            ███    ██       ███    ██   ##
##   █████████      ███████         █████████   ##
##                                              ##
##  ESSE MATERIAL FAZ PARTE DA COMUNIDADE ZDG   ##
##                                              ##
##        PIRATEAR ESSA SOLUÇÃO É CRIME.        ##
##                                              ##
##    © COMUNIDADE ZDG - comunidadezdg.com.br   ##
##                                              ##
===================================================

===================================================
## ACESSO SSH E FTP NA VPS ##
https://www.bitvise.com/
===================================================

#1 INSTALAR VPS
UBUNTU 20.04

#2 ATUALIZAR VPS
sudo apt -y update && apt -y upgrade
sudo reboot

#3 CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS
TYPEBOT: typebot.comunidadezdg.com.br
BOT: bot.comunidadezdg.com.br
STORAGE: storage.comunidadezdg.com.br
WHATICKET: whaticketapp2.comunidadezdg.com.br
API:  whaticketapi2.comunidadezdg.com.br

#4 CHECAR PROPAGAÇÃO DO DOMÍNIO
https://dnschecker.org/

#5 CRIAR CREDENCIAIS DO E-MAIL PARA O TYPEBOT
EMAIL: zdgads@gmail.com
SENHA: sdxgwgbfilmylpfj
SMTP: smtp.gmail.com
PORTA: 465
SECURE: true
KEY: 9bd08a339fb03237e02cb5ce0f430675

===================================================
## TYPEBOT ##
===================================================

#6 COPIAR A PASTA PARA ROOT E RODAR OS COMANDOS ABAIXO
sudo chmod +x ./comunidadezdg.com.br/typebot.sh
cd ./comunidadezdg.com.br
sudo ./typebot.sh

===================================================
## WHATICKET ##
===================================================

#7 RODAR OS COMANDOS ABAIXO
sudo chmod +x ./comunidadezdg
sudo ./comunidadezdg

===================================================
## ACESSOS ##
===================================================

# TYPEBOT
Gerar convite via e-mail

# WHATICKET
login: admin@comunidadezdg.com.br
senha: admin

===================================================
