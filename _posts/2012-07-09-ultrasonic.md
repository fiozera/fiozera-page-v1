---
layout: post
title: Ultrasonic surface
snippet:
repository: https://github.com/andrebla/ultrasonicsurface
youtube: 
- nP65q2B6wzs
- PwEjEgAqbCw
thumbnail: ultrasonic.JPG
pictures: 
- http://farm8.staticflickr.com/7255/7539897300_d770a190bb_z.jpg
- http://farm9.staticflickr.com/8292/7539910386_5b3e479b2e_z.jpg
---

This project is a continuation of our prior development with
interaction interfaces. We are testing open hardware options and
simple solutions that can capture hands movement and translate into
messages to the computer. This time we have used a ultra-sonic sensor
— an alternative to our prior experiment [REF] where it was used an
infra-red sensor. The general idea is to measure the distance of an
object, say your hand, from the actual sensor. In order to send the
information to the computer, it was decided, again, to use the
keyboard function that is provided as part of the Leonardo Arduino
interface — in this case our FZDUINO.

The sensor was placed at the right side of the monitor so purposed to
measure distances within the range of the viewport of the monitor.
When the device is turned on, it measures the distance of the first
object it finds and uses it as the upper limit so any objects beyond
that point won't be informed to the computer. Because it finds the
border of the monitor ( think border is required here or something
equivalent ) it works as a self-calibrating device. After the initial
calibration function it starts to monitor if any object appears within
the range ( from minimal detection point to the calibration max ) and
when it finds a keyboard character is passed between A to Z depending
on the distance.

Arduino Leonardo compatible board [FZDUINO](http://fiozera.com.br/2012/01/01/fzduino.html)


Arduino Reference - [Mouse and Keyboard libraries](http://arduino.cc/en/Reference/MouseKeyboard)


Projeto apoiado por [TelaSocial](http://telasocial.com/)


Veja mais em [TelaSocial – Experimentação com interação e toque](http://blog.telasocial.com/experimentacao-com-interacao-e-toque)