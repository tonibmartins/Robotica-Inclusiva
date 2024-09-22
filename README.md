# Robotica-Inclusiva

# Material de Estudo - Prova de Robotica

Este repositório contém o material de estudo para a prova de Robotica, cobrindo os principais tópicos abordados no simulado. Cada seção oferece explicações detalhadas, exemplos práticos e questões de revisão para ajudar na preparação para a prova.

## Conteúdo

### 1. PWM (Modulação por Largura de Pulso) e Saída Analógica
- **Descrição:** Introdução à técnica de PWM e como ela é usada para simular sinais analógicos utilizando sinais digitais.
- **Exemplo:** Código de exemplo para controlar a intensidade de um LED usando PWM no Arduino.
- **Questão de Revisão:** Calcule o valor médio de uma onda PWM com duty cycle de 60% para um sinal de 0V a 5V.

### 2. Eletrônica Embarcada
- **Descrição:** Visão geral de sistemas embarcados, incluindo microcontroladores e sua interação com o ambiente físico.
- **Exemplo:** Explicação sobre o uso de PWM em microcontroladores para controle de dispositivos.
- **Questão de Revisão:** Explique como um microcontrolador pode usar PWM para controlar a velocidade de um motor.

### 3. Sensores Ultrassônicos e Controle de Servo Motor com Arduino
- **Descrição:** Funcionamento de sensores ultrassônicos e controle de servo motores utilizando Arduino.
- **Exemplo:** Código de exemplo para medir distância usando um sensor ultrassônico com Arduino.
- **Questão de Revisão:** Descreva como medir a distância usando um sensor ultrassônico com Arduino.

### 4. Componentes de Robôs
- **Descrição:** Descrição dos principais componentes de um robô, incluindo sensores, atuadores, controladores e corpo físico.
- **Exemplo:** Exemplo de como um robô usa sensores para evitar obstáculos.
- **Questão de Revisão:** Quais são as funções principais de um sensor em um robô?

### 5. Divisor de Tensão e LDR
- **Descrição:** Explicação sobre divisores de tensão e funcionamento de resistores dependentes de luz (LDRs).
- **Exemplo:** Como calcular a tensão em um ponto de um circuito divisor de tensão usando um LDR.
- **Questão de Revisão:** 

  Dado um circuito divisor de tensão onde:

  - A resistência do LDR é de \( 2k\Omega \).
  - O resistor fixo tem uma resistência de \( 3k\Omega \).
  - A tensão de entrada no circuito é de 5V.

  **Pergunta:** Qual é a tensão medida entre o LDR e o resistor fixo?

  **Dica:** Use a fórmula:

  \[
  \text{Tensão medida} = \frac{\text{Resistência do LDR}}{\text{Resistência do LDR} + \text{Resistência do Resistor Fixo}} \times \text{Tensão de Entrada}
  \]

  Substitua os valores fornecidos e calcule a tensão medida.


### 6. Conversão Analógico-Digital (ADC)
- **Descrição:** Processo de conversão analógico-digital, cobrindo amostragem, quantização e resolução de ADCs.
- **Exemplo:** Explicação sobre a frequência de amostragem e níveis de quantização.
- **Questão de Revisão:** Explique a diferença entre amostragem e quantização em um conversor A/D.

### 7. Controladores em Robótica
- **Descrição:** Tipos de controladores usados em robótica, incluindo controladores PID.
- **Exemplo:** Aplicação de um controlador PID para manter a temperatura constante em um sistema.
- **Questão de Revisão:** Como um controlador PID pode ser implementado para controlar a velocidade de um motor?

### 8. Arduino e Shields
- **Descrição:** Uso de PWM no Arduino para controle de dispositivos e a utilização de shields para expandir suas funcionalidades.
- **Exemplo:** Código de exemplo para controlar o brilho de um LED usando a função analogWrite().
- **Questão de Revisão:** Como você usaria a função analogWrite() para controlar o brilho de um LED?
