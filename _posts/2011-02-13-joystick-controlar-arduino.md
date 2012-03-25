---
layout: post
title: Como usar joysticks para controlar seus projetos com Arduino
snippet: Mantendo o controle
repository: https://github.com/andrebla/ghlights
youtube: Ak8JPkltOgs
thumbnail: joystick-controlar-arduino.jpg
---

Neste primeiro post vou descrever através de um simples projeto uma forma de 
utilizar seus periféricos (mouse, teclado, joysticks etc.) conectados ao pc 
como entrada de parâmetros para o Arduino utilizando a comunicação serial.
A forma mais trivial que encontrei para fazer isto foi através do Processing, 
utilizando a biblioteca proCONTROLL, escrita por Christian Riekoff, a documentação 
detalhada e cheia de exemplos facilita bastante na hora de escrever o código. 
Fiz esse projeto com a simples intenção de entender melhor a comunicação serial 
com o processing e brincar com a biblioteca proCONTROLL.
Vamos para o projeto em si, ele consiste em mandar simples comandos com meu 
controle de Guitar Hero para acionar leds, enquanto um botão está pressionado o 
led referente a este botão fica aceso.


[Outro video](http://www.youtube.com/embed/U-ofDQl6WSc)


Links
-----
* [Arduino](http://arduino.cc/)
* [Processing](http://www.processing.org/)
* [proCONTROLL](http://creativecomputing.cc/p5libs/procontroll/)
