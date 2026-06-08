# GS-edge-1

# Modo Sobrevivência Offline - LifeSignal

# Descrição do Projeto

  O Modo Sobrevivência Offline é um sistema de monitoramento desenvolvido com Arduino que auxilia usuários em situações de emergência ou sobrevivência. O projeto utiliza sensores para identificar condições ambientais críticas e informar o usuário através de alertas visuais e sonoros.
  O sistema funciona mesmo sem conexão com a internet, tornando-se uma alternativa viável para locais remotos, áreas afetadas por desastres naturais ou situações onde não há acesso à rede.

# Objetivo da Solução

  O objetivo do projeto é fornecer uma ferramenta simples e acessível para monitoramento ambiental em tempo real, auxiliando usuários na identificação de possíveis riscos ao seu redor.
A solução busca: Aumentar a segurança em situações de emergência, fornecer alertas imediatos ao usuário, operar sem necessidade de conexão com a internet, demonstrar a aplicação prática de sensores e sistemas embarcados e incentivar o uso da tecnologia em projetos de prevenção e sobrevivência.

# Componentes Utilizados

1 Arduino Uno
1 Sensor Ultrassônico PING
1 LED Verde
1 LED Amarelo
1 LED Vermelho
3 Resistores 220
1 Buzzer 
Diversos Jumpers
1 Cabo USB

# Explicação do Funcionamento

  O sistema monitora continuamente a distância entre o sensor ultrassônico e objetos próximos.
  Com base nos valores capturados, o Arduino interpreta o nível de risco e fornece alertas por meio de LEDs coloridos e de um buzzer.

Nível Seguro:
Quando a distância detectada é considerada segura: LED verde aceso; Buzzer desligado.
Indica que não há obstáculos próximos ou situações de risco imediato.

Nível de Atenção:
Quando um objeto se aproxima: LED amarelo aceso; Buzzer desligado.
Indica que o usuário deve permanecer atento ao ambiente.

Nível de Alerta:
Quando a distância atinge um valor crítico: LED vermelho aceso; Buzzer ativado.
Indica perigo ou necessidade de ação imediata.
Esses alertas permitem que o usuário reaja rapidamente a possíveis obstáculos ou ameaças no ambiente.

# Estrutura do Circuito

Sensor Ultrassônico PING:
GND - GND
5V - 5V
SIG - Pino digital 7

LED Verde
Pino Digital 13
Resistor 220 Ω
GND

LED Amarelo
Pino Digital 12
Resistor 220 Ω
GND

LED Vermelho
Pino Digital 11
Resistor 220 Ω
GND

Buzzer
Pino Positivo - Pino Digital 8
Pino Negativo - GND

# Instruções de Execução

1. Montagem
Monte o circuito conforme o esquema eletrônico desenvolvido no Tinkercad.
2. Programação
Abra a IDE Arduino e carregue o código do projeto.
3. Upload
Conecte o Arduino ao computador e envie o programa para a placa.
4. Testes
Aproxime objetos do sensor ultrassônico para verificar:
Acendimento dos LEDs.
Mudança dos níveis de alerta.
Acionamento do buzzer em situações críticas.

# Aplicações do Projeto

O Modo Sobrevivência Offline pode ser aplicado em:
Situações de emergência.
Ambientes sem acesso à internet.
Acampamentos e trilhas.
Monitoramento de obstáculos.
Sistemas básicos de segurança.
Projetos educacionais envolvendo Arduino e sensores.

# Integrantes do Grupo

Guilherme Alves - RM:570551
Sofia Costa - RM:570339
Sophia Trindade - RM:570349
Gabriela Gomes - RM:568797
Gabriell Santos - RM:574134

# Conclusão

O projeto Modo Sobrevivência Offline demonstra como sistemas embarcados podem ser utilizados para fornecer informações importantes ao usuário mesmo em ambientes sem conectividade. Utilizando sensores, alertas visuais e sonoros, a solução contribui para a segurança e conscientização em situações que exigem atenção rápida, reforçando o potencial da tecnologia como ferramenta de apoio em cenários de sobrevivência e emergência.
