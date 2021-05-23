# Projeto-loT
Repositório destinado para o projeto de loT Mackenzie 

Como Funciona?
Logo após a compilação, o sensor DHT11 vai fazer uma leitura da Temperatura e Umidade, e com isso dependendo dos resultados acontecerá ações dentro do sistema como:
Resultado Umidade: Abaixo de 20% -> led vermelho ascende, Buzzer apita e no Serial tem uma mensagem "Necessidade baixa de hidratação"
Resultado Umidade: Acima de 20% e abaixo de 70% -> Led Verde ascende, Buzzer apita e no Serial tem uma mensagem "Necessidade média de hidratação.
Resultado umidade: Acima de 70% -> dois leds ascendem, buzzer apita e no serial tem uma mensagem "Necessidade alta de hidratação"

Todas as infos devem ir para o app MQTT Dash.

Para a leitura do código -> acesse a pásta Código.
Para entender a montagem e o funcionamento do código-> Projeto - representações

O que foi utilizado?
- Arduino Uno - Base do projeto
- Sensor de Temperatura e Umidade DHT11 - Para as leituras
- Kit Jumpers - conexão dos equipamentos entre o protoboard e arduino
- Cabo USB com saída USB - Conectar o arduino para o software de desenvolvimento.
- ESP01- Modulo wifi
- LED vermelho e LED Verde - Atuadores
- Buzzer- Atuador de efeito sonoro
- Protoboard - Conexão
- Resistores - Conexão dos leds
- 
