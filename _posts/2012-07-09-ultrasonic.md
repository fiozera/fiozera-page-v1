---
layout: post
title: Ultrasonic surface
snippet: Tá ouvindo?
repository: https://github.com/andrebla/ultrasonicsurface
youtube: nP65q2B6wzs
thumbnail: ultrasonic.JPG
pictures: 
- http://farm8.staticflickr.com/7255/7539897300_d770a190bb_z.jpg
- http://farm9.staticflickr.com/8292/7539910386_5b3e479b2e_z.jpg
---

Prosseguindo com o estudo de superfícies que utilizem gestos ou toques como 
formas de interação desta vez foi feito o uso de um módulo ultrasonico, em 
alternativa ao uso de sensores infra-vermelho como anteriormente. A ideia 
agora é medir a distância entre a mão de um usuário e um ponto de referência, 
onde se encontra o sensor ultrassônico e enviar esta informação a um computador. 
Aqui mais uma vez é utilizada a função de keyboard das placas compatíveis Arduino 
Leonardo, caso da FZDUINO.  
O sensor foi colocado do lado direito do monitor de modo a medir distâncias 
referentes a área central do monitor. Dependendo da região uma tecla correspondente 
é enviada.  
Nesta aplicação um jumper foi utilizado para habilitar a função keyboard, quando o 
jumper é desconectado um conjunto de 4 leds é responsável por indicar em qual área 
a mão do usuário está.


Placa Arduino Leonardo compatível [FZDUINO](http://fiozera.com.br/2012/01/01/fzduino.html)


Arduino Reference - [Mouse and Keyboard libraries](http://arduino.cc/en/Reference/MouseKeyboard)


Projeto apoiado por [TelaSocial](http://telasocial.com/)


Veja mais em [TelaSocial – Experimentação com interação e toque](http://blog.telasocial.com/experimentacao-com-interacao-e-toque)