---
layout: post
title: Superfície de toque
snippet: Pra sujar o monitor
repository: https://github.com/andrebla/touchsurface
youtube: 
- emBm9OQ2CPE
thumbnail: superficie-de-toque.jpg
pictures: 
- http://farm8.staticflickr.com/7141/6709081331_caabcf37d9_z.jpg
- http://farm8.staticflickr.com/7020/6709078249_da8dd9035a_z.jpg
- http://farm8.staticflickr.com/7149/6703201993_590ed47c46_z.jpg
---

A ideia de se fazer uma superficie de toque para telas finas de grandes dimensões 
parece algo muito atrativo, no entanto as tecnologias atuais empregadas na maioria 
dos dispositivos móveis como celulares trazem elevado custo para dispositivos de 
maior tamanho. A proposta deste projeto é a confecção de um protótipo de uma 
superfície delimitada por uma estrutura matricial de diodos emissores de luz 
infra-vermelha e foto-transistores. Uma desvantagem apresentada por esse tipo 
de estrutura matricial com sensores de luz é a incapacidade de se construir 
superfícies multitoque, no entanto esse tipo de estrutura possui um custo baixo 
para implementação.  
Uma placa de controle é responsável por fazer o monitoramento dos sensores e 
quando um feixe de luz infra-vermelha é interrompido por um objeto as 
informações de posição são enviadas para um microcontrolador que por sua 
vez a transmite para um computador.  
Fazendo uso da capacidade de se projetar dispositivos USB presente no 
microcontrolador ATMEGA32U4 usado no FZDUINO, placa Arduino Leonardo compatível, 
o protótipo construído com um número baixo de sensores foi projetado como um 
teclado, assim dependendo da área de toque um carácter é enviado ao computador.  
Para realizar os testes da estrutura foram montadas duas placas, uma com os 
emissores e outra com os receptores, que podem ser ligadas em cascata.


Projeto apoiado por [TelaSocial](http://telasocial.com/)


Veja mais em [TelaSocial – Experimentação com interação e toque](http://blog.telasocial.com/experimentacao-com-interacao-e-toque)