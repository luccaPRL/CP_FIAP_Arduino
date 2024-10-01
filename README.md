# CP_FIAP_Arduino

Descrição do Projeto: Sistema de Monitoramento de Luminosidade para Armazenamento de Vinho
O projeto consiste em um sistema de monitoramento de luminosidade utilizando um Arduino, que é essencial para garantir a qualidade do vinho armazenado na Vinheria Agnello. Este sistema captura dados de luminosidade do ambiente e indica se as condições estão adequadas para o armazenamento do vinho. Dependendo dos níveis de luminosidade, o sistema utiliza LEDs e um buzzer para sinalizar os estados do ambiente.

Funcionalidades:
LED Verde: Indica que as condições de luminosidade estão OK (acima de 550).
LED Amarelo: Indica que as condições de luminosidade estão em nível de alerta (entre 350 e 550).
LED Vermelho: Indica que as condições de luminosidade estão problemáticas (abaixo de 350).
Buzzer: Emite um som quando as condições estão em alerta ou problema.
Dependências:
Para reproduzir este projeto, você vai precisar dos seguintes componentes:

Hardware:

1 x Arduino Uno
1 x LDR (Light Dependent Resistor)
1 x Buzzer
3 x LEDs (Verde, Amarelo e Vermelho)
3 x Resistores de 220Ω (para os LEDs)
1 x Resistor de 10kΩ (para o LDR)
Fios Jumpers
1 x Protoboard
Software:

Arduino IDE para programar o Arduino.
Conhecimento básico em eletrônica para realizar as conexões.
Como Reproduzir o Projeto:
1) Montagem do Circuito:
Siga os passos abaixo para montar o circuito no protoboard:

Conexões do LDR:

Um terminal do LDR deve ser conectado ao pino A0 do Arduino.
O outro terminal do LDR deve ser conectado ao 5V do Arduino.
Um resistor de 10kΩ deve ser conectado entre o pino A0 e o GND do Arduino.
Conexões dos LEDs:

Conecte o LED Verde ao pino 7 do Arduino (com um resistor de 220Ω em série).
Conecte o LED Amarelo ao pino 6 do Arduino (com um resistor de 220Ω em série).
Conecte o LED Vermelho ao pino 5 do Arduino (com um resistor de 220Ω em série).
Conexões do Buzzer:

Conecte o terminal positivo do buzzer ao pino 4 do Arduino e o terminal negativo ao GND.

2) Código do Arduino:
Copie e cole o código abaixo no Arduino IDE.
Localiza-se dentro do mesmo repositorio 

3) Teste do Sistema:
Carregue o Código: Carregue o código no Arduino usando o Arduino IDE.
Monitore os LEDs e o Buzzer: Observe o funcionamento do sistema e ajuste os limites conforme necessário.
Verifique a Luminosidade: Cubra o LDR ou ilumine-o para ver como os LEDs e o buzzer reagem.
Conclusão:
Este projeto é uma forma simples e eficaz de monitorar a luminosidade em ambientes de armazenamento de vinho, ajudando a garantir a qualidade do produto. Você pode expandir o sistema adicionando sensores para temperatura e umidade, criando um sistema de monitoramento completo para a vinheria.
