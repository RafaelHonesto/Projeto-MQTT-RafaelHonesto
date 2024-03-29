### Projeto-MQTT-RafaelHonesto  
Repositório criado para o projeto desenvolvido durante a Sprint 8 do Curso Técnico em Redes de computadores da Escola SENAI de informática. :smiley:

# Objetivo:

O objetivo do projeto é fazer uma ferramenta de alerta e monitoramento utilizando um [Arduino Uno](https://www.arduino.cc/) e um sensor Magnético para o monitoramento da porta de um RACK de rede, desta forma tendo um retorno remoto do estado da porta que pode ser *Aberto* ou *Fechado*. Essa informação é enviada pela internet utilizando o protocolo [MQTT](https://mqtt.org/) (Message Queuing Telemetry Transport) para um outro servidor hospedado na **AWS** (*Amazon Web Service*) que exibe a mensagem no aplicativo para SmartPhone [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=pt_BR&gl=US) conforme a imagem em anexo:


![Topologia lógica do projeto](https://user-images.githubusercontent.com/73251227/106644250-9fafc480-6569-11eb-81d9-82ff9a5cc126.PNG)

No Arduino as bibliotecas são trechos de softwere utilizados para funções especificas e neste projeto utilizamos as seguintes biblotecas :books::

* [UIPEthernet](https://github.com/UIPEthernet/UIPEthernet)

* [PubsubClient](https://github.com/knolleary/pubsubclient) 

# Materiais utilizados para a execução do projeto:

* [Arduino Uno](https://www.arduino.cc/)

* [Módulo Ethernet (ENC28J60)](https://www.arduino.cc/search?q=M%C3%B3dulo%20Ethernet%20%28ENC28J60%29)

* [Sensor Magnético (MC-38)](https://blogmasterwalkershop.com.br/arduino/como-usar-com-arduino-sensor-magnetico-com-fio-para-alarme-mc-38/)

* [Jumpers](https://www.arduino.cc/search?q=jumpers&tab=store)

# Circuito 



![Entregável aula 99²](https://user-images.githubusercontent.com/73251227/106649666-ab52b980-6570-11eb-98f2-cba4f8a6c201.PNG)

**Autor: Rafael Honesto.**

[![Instagram Badge](https://img.shields.io/badge/-Instagram-black?style=flat-square&logo=Instagram&logoColoer-white&link=https://www.instagram.com/rafaelhonesto/)](https://www.instagram.com/rafaelhonesto/)

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-black?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafael-costa-c-honesto-3b46b2205/)](https://www.linkedin.com/in/rafael-costa-c-honesto-3b46b2205/)
