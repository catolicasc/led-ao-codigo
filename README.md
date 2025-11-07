# Engenharia de Software — Do LED ao Código: Introdução ao Arduino

## Visão Geral do Módulo
**Tema central:** Do LED ao Código — Introdução ao Arduino  
**Carga horária:** 3 encontros 3 horas cada)  
**Objetivo geral:** Compreender a relação entre software e hardware, aplicando princípios de engenharia de software no desenvolvimento de pequenos projetos com Arduino.

---

## Aula 1 — Fundamentos da Engenharia de Software e o Universo Arduino

### Objetivos
- Entender o papel da engenharia de software em sistemas embarcados.  
- Conhecer o Arduino, sua estrutura e linguagem (C/C++ simplificado).  
- Criar o primeiro programa (“Blink”) e compreender seu fluxo lógico.

### Conteúdos
1. O que é Engenharia de Software aplicada a hardware.  
2. O ecossistema Arduino: IDE, placa, portas digitais e analógicas.  
3. Estrutura básica de um código Arduino (`setup()` e `loop()`).  
4. Exemplo prático: Piscar um LED (Blink)  
   - Explicação dos pinos digitais.  
   - Introdução a `digitalWrite()` e `delay()`.

### Materiais
- Arduino Uno ou Nano  
- Cabo USB  
- LED, resistor de 220Ω, protoboard e jumpers

### Atividade prática
- Montar o circuito e fazer o LED piscar.  
- Modificar o tempo do `delay` e observar o comportamento.  

### Discussão
- O que é um “loop infinito”?  
- Como o software controla o hardware?

---

## Aula 2 — Lógica de Programação e Interação com Sensores

### Objetivos
- Aplicar estruturas de controle e variáveis no Arduino.  
- Ler entradas digitais (botões, sensores simples).  
- Criar uma lógica de decisão em código.

### Conteúdos
1. Variáveis, tipos e operadores.  
2. Estruturas condicionais: `if`, `else`.  
3. Leituras de entrada: `digitalRead()`.  
4. Exemplo prático: Botão que acende LED  
   - “Se o botão for pressionado, acender o LED.”  
   - Discussão sobre *debounce* e lógica digital.

### Materiais
- Arduino  
- Protoboard, LED, botão, resistores  
- Jumpers

### Atividade prática
- Criar um “interruptor inteligente”: LED acende com um clique e apaga com outro.  
- Implementar uma variável de estado (`bool ledOn`).

### Reflexão
- Como o software lida com sinais elétricos?  
- Qual seria o impacto de um erro lógico no hardware?

---

## Aula 3 — Pequenos Sistemas: Pensando como Engenheiro de Software

### Objetivos
- Integrar conceitos de software e hardware em um mini sistema.  
- Aplicar boas práticas de engenharia (clareza, modularização).  
- Compreender o processo de documentação de projeto.

### Conteúdos
1. Funções e modularização no Arduino.  
2. Introdução a sensores analógicos (LDR, potenciômetro).  
3. Exemplo prático: Controle de brilho do LED com potenciômetro.  
4. Discussão: padrões de projeto e reutilização de código.

### Materiais
- Arduino  
- Protoboard  
- LED, resistores, potenciômetro  
- Jumpers  

### Atividade prática
- Ler o valor do potenciômetro (`analogRead()`), mapear (`map()`) e ajustar o brilho (`analogWrite()`).

### Atividade final
- Em duplas, criar um mini projeto integrado:  
  - Exemplos: “Semáforo inteligente”, “Luz ambiente automática”, “Sensor de presença”.  
- Documentar: circuito, código e lógica.
