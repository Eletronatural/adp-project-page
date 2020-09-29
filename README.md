# All Devices Plattform

O All Devices Plattform (ou ADP) é um sistema de gerenciamento de dispositivos IoT, como atuadores de luzes, portões eletrônicos, fechaduras digitais e sensores de temperatura, de fácil configuração e utilização. Sua principal aplicação é no ambiente doméstico, em casas e condomínios de casas ou de apartamentos mas também pode ser configurado para instalações comerciais e industriais.

O sistema é composto por três tipos de módulos, o gerenciador, o controlador e os dispositivos controlados.

## Especificação Técnica

Os módulos gerenciador e controlador foram implementados em linguagem de programação Java e são executados em um computador embarcado dedidaco (Raspberry Pi).

Os dispositivos, em sua maioria, foram implementados em linguagem de programação C/C++ e são executados em microcontroladores embarcados dedicados (Arduino / ESP8266)

O sistema é flexível para evolução, possibilitando a adição de novas funcionalidades e o controle de novos tipos de dispositivos.

A comunicação entre o controlador e os dispositivos é feita através de fila de mensagens, utilizando o protocolo MQTT.

O acesso dos usuários ao sistema é feito através do protocolo HTTP, contemplando os requisitos de segurança da Internet (modelo OAuth2).

## Contato

Arquiteto e desenvolvedor: Gustavo Rubin (gusrubin@gmail.com)
