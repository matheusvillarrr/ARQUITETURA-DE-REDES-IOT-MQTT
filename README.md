# ARQUITETURA-DE-REDES-IOT-MQTT

Este projeto demonstra a comunicação via MQTT utilizandopaho-mqtt em Python

publisher.py:
subscriber.py: Escuta mensagens

Python 3 instalado
Instalar a biblioteca necessária executando:
bash
pip install paho-mqtt
 Como usar
Executar o Assinante (subscriber.py)
Este script fica aguardando mensagens publicadas no tópico MQTT definido. Para executá-lo:

bash

python subscriber.py
Executar o Publicador (publisher.py)
Este script permite enviar mensagens para o tópico MQTT. Para executá-lo:

bash

python publisher.py
Digite a mensagem e pressione Enter para publicá-la.

Configurações MQTT
Broker: broker.hivemq.com
Porta: 1883
Tópico do Publicador: senai/dev
Tópico do Assinante: senai/miguel
