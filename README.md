# Projeto MQTT Arduino
# Objetivo do Projeto

O projeto visa monitorar o acesso ao servidor utilizando o protocolo MQTT através do Arduino Uno.  Usando  um sensor magnético conectado ao Arduino podemos  monitorar se  a porta  do rack está aberta ou fechada. Essa informação é enviada via internet  utilizando o protocolo MQTT (Message Queuing Telemetry Transport) para um servidor MQTT hospedado na Amazon Web Service (AWS). A mensagem será exibida em um Client MQTT  atravéz do aplicativo (MQTT DASH) instalado em um celular.

*_Esquematização do processo que a informação percorrerá:_*

![alt text](https://camo.githubusercontent.com/7beef2d4780d87a603d7de49b2da0467c8537dff96575b628a04bd4010ebb1cc/68747470733a2f2f692e696d6775722e636f6d2f4d576870586b562e706e67)

*_Bibliotecas utilizadas:_*
- UIPEthernet
- PubSubClient

# Circuito

A projeção virtual a baixo nos permite observar a conexão do sensor que será responsável por uma parte importante do projeto ao Arduino. Contudo, podemos analisar ilustradamente que as conexões coloridas são referentes ao Módulo Ethernet e as brancas são referentes ao sensor magnético utilizado.

![alt text](https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67)

# Materiais

- Arduino Uno
- Módulo Ethernet (ENC28J60)
- Sensor Magnético (MC-38)
- Jumpers

*_Autora:_* Laura de Lima Santos
