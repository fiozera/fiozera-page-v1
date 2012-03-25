---
layout: post
title: fzrcontroll – Usando um joystick para controlar um carro de controle remoto
snippet: Redundância?
repository: https://github.com/andrebla/fzrcontroll
youtube: U-ofDQl6WSc
thumbnail: fzrcontroll.jpg
---

A maioria dos modelos controlados por radio frequência usa em seus controladores 
o principio de divisor de tensão, um circuito é resposável por medir a tensão 
de um divisor resistivo que é enviado como comando que corresponde a uma ação 
no modelo. Usando uma saída PWM do microcontrolador e um filtro tipo passa baixa 
é possível controlar um carro de controle remoto com outros dispositivos como 
um joystick de videogame, ou mesmo um teclado e um mouse através do Processing, 
usando a biblioteca proCONTROLL, escrita por Christian Riekoff.
O repositório contém os códigos para o Arduino e para o Processing.

Links
-----
* [Arduino](http://arduino.cc/)
* [Processing](http://www.processing.org/)
* [proCONTROLL](http://creativecomputing.cc/p5libs/procontroll/)