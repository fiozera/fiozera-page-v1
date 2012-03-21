---
layout: post
title: FZDUINO – Placa compatível Arduino Leonardo
repository: https://github.com/andrebla/fzduino
youtube: Ak8JPkltOgs
---

Com o propósito de fazer uma placa compatível Arduino de baixo custo que pudesse 
ser acomodada em uma matriz de contatos e após a liberação da versão release 
candidate 1.0 da IDE do Arduino, que já contém o bootloader empregado aqui, a 
possibilidade de uma placa utilizando o microcontrolador Atmel AVR atmega32u4, 
que já possui suporte USB, se tornou uma tarefa mais simples.
O suporte a USB nativo dado pelo microcontrolador dispensa o uso de conversores 
serial/USB necessários em outras placas a exemplo do Arduino Duemilanove e UNO 
o que torna a placa mais simples e reduzida, embora o microcontrolador atmega32u4 
somente exista em encapsulamento smd o que dificulta a montagem para aqueles que 
não possuem muita pratica em soldagem desse tipo de componente. Para reduzir ainda 
mais as dimensões da placa para permitir o uso em uma matriz de contatos também 
foram empregados resistores e capacitores smd.
Para a programação inicial do bootloader no microcontrolador presente na placa 
foi utilizado o programador USBTINYISP, já detalhador em outro post, e a IDE 
Arduino 1.0 release candidate.
O repositório no github contém os arquivos da placa feitos no software Eagle.

[Arduino 1.0 Release Candidate](http://code.google.com/p/arduino/wiki/Arduino1)