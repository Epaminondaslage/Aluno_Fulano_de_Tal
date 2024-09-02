# Montagem Básica  de Contagem de Pressionamentos de Botão

## Descrição

Este projeto demonstra como contar o número de vezes que um botão é pressionado utilizando um Arduino. O objetivo é detectar as transições do estado do botão de desligado (LOW) para ligado (HIGH) e contabilizar cada pressionamento. Os resultados são exibidos no Serial Monitor.

## Funcionamento

O programa funciona da seguinte maneira:
1. **Leitura do Estado do Botão**: A cada iteração do loop principal, o Arduino lê o estado atual do botão.
2. **Comparação de Estados**: O estado atual do botão é comparado com o estado anterior (armazenado em uma variável).
3. **Detecção de Pressionamento**: Se o estado atual for diferente do estado anterior e for igual a HIGH, o contador de pressionamentos é incrementado.
4. **Exibição no Serial Monitor**: A cada incremento, o valor da contagem é enviado ao Serial Monitor para visualização.

## Materiais Necessários

- **Arduino Uno**
- **1 Botão de pressão**
- **1 Resistor de 10 kΩ (pull-up)**
- **Fios de conexão** (jumpers)
- **Protoboard**

## Montagem do Circuito

1. **Conecte o Botão**:
   - Conecte um terminal do botão ao pino digital 2 do Arduino.
   - Conecte o outro terminal do botão a uma fonte de 5V.
   - Conecte um resistor de 10 kΩ entre o pino 2 e o GND para configurar o resistor pull-up.

2. **Protoboard e Fios de Conexão**:
   - Use a protoboard para montar o circuito e organizar as conexões.
   - Utilize fios de conexão (jumpers) para ligar os componentes ao Arduino.



