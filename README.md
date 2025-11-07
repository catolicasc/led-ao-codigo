# Engenharia de Software — Do LED ao Código: Introdução ao Arduino

## Sobre o Módulo
**Tema:** Do LED ao Código — Introdução ao Arduino  
**Duração:** 3 aulas (3 horas cada)  
**Objetivo:** Entender como o software controla o hardware, criando pequenos projetos com o Arduino.

---

## Aula 1. Conhecendo o Arduino e o Primeiro Código

### O que vamos aprender
- O que é o Arduino e para que serve.  
- Como funciona um programa simples.  
- Fazer o primeiro LED piscar.

### Conteúdo
1. O que é Engenharia de Software (de forma simples).  
2. Partes do Arduino: placa, portas, IDE (programa onde escrevemos o código).  
3. Estrutura básica do código (`setup()` e `loop()`).  
4. Exemplo prático: LED piscando.  
   - Como ligar o LED no pino certo.  
   - Usando `digitalWrite()` e `delay()`.

### Materiais
- Thinkercad
- LED, resistor de 220Ω, protoboard e jumpers

### Atividade prática
- Montar o circuito e fazer o LED piscar.  
- Trocar o tempo do `delay` e observar o resultado.

### Discussão
- O que significa o código ficar “rodando pra sempre”?  
- Como o software faz o LED piscar?

---

## Aula 2. Lógica e Sensores: Fazendo o Arduino Pensar

### O que vamos aprender
- Usar **variáveis** e **condições** no código.  
- Ler informações de botões e sensores.  
- Fazer um LED acender quando o botão for pressionado.

### Conteúdo
1. Variáveis e tipos básicos.  
2. Condições: `if` e `else`.  
3. Leitura de entradas com `digitalRead()`.  
4. Exemplo prático: botão que acende o LED.  
   - “Se apertar o botão → LED acende”.

### Materiais
- Thinkercad
- LED, botão, resistores  
- Protoboard e jumpers

### Atividade prática
- Criar um LED que acende com um clique e apaga com outro.  
- Usar uma variável (`ledOn`) para guardar o estado.

### Discussão
- Como o Arduino sabe que o botão foi apertado?  
- O que acontece se o código tiver um erro?

---

## Aula 3. Criando um Mini Projeto com o Arduino

### O que vamos aprender
- Juntar tudo o que aprendemos para criar um pequeno sistema.  
- Organizar o código e usar funções simples.  
- Usar sensores analógicos, como o potenciômetro.

### Conteúdo
1. Funções: dividir o código em partes menores.  
2. Leitura de sensores analógicos com `analogRead()`.  
3. Exemplo prático: controlar o brilho do LED com um potenciômetro.  
4. Como pensar em um projeto completo.

### Materiais
- Arduino  
- LED, potenciômetro, resistores  
- Protoboard e jumpers

### Atividade prática
- Ler o valor do potenciômetro e controlar o brilho com `analogWrite()` e `map()`.

### Projeto final (em dupla)
- Criar um mini projeto usando o que aprendeu.  
  - Exemplos: **Semáforo inteligente**, **Luz automática**, **Sensor de presença**.  
- Documentar o projeto: circuito, código e explicação.

---
