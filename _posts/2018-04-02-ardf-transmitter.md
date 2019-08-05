---
title: ARDF Transmitter
layout: with_title
---

The aim of this project was the development of a universal, practicable ARDF
transmitter for the Austrian Amateur Radio Association (ÖVSV). Amateur Radio
Direction Finding or short ARDF is a racing contest where contestants 
use special radio receivers helping them to search and find multple transmitters
hidden in the surrounding terrain. The concept for this transmitter is 
based on the diploma project “ARDF Duoband Transmitter” by Simon Außerlechner, 
Clemens Moroder and Gerald Renner at HTL Anichstraße from 2006, with the design 
revised and partly extended with new functionalities.

The ARDF transmitter is 
able to transmit automatically both in the 80m- and in the 2m HAM frequency band.
Aditionally, a SWR meter makes the process of tuning the antennas easier when 
placing and installing the transmitters in the terrain. Registration of the 
participants during the competition is accomplished via RFID-tags in conjunction 
with an integrated RFID-reader.

The configuration of the transmitter prior to 
the event as well as the analysis of the competitor's data afterwards is carried 
out digitally via a PC interface. The elaborated hardware and software design is 
tested on a prototype, where it is found that most of the requirements are met.

Code for the microcontroller is written in C using the avr-gcc compiler. The
PC software is developed in Python using the wxWidgets Python bindings as a
GUI framework.

Source code can be found on [Github](https://github.com/simonkaufmann/ARDF-Transmitter).  

Additional material is available on the [project page](http://ardf.heka.or.at/).   

The thesis document (written in German) can be downloaded [here](http://ardf.heka.or.at/amateurfunkpeilsender.pdf).

<div class="w3-row-padding">
<div class="w3-half">
  <img src="/res/ardf/software.png" style="max-width: 100%;" onclick="onClick(this, '/res/ardf/software.png')"/>
  <img src="/res/ardf/dds.jpg" style="max-width: 100%;" onclick="onClick(this, '/res/ardf/dds.jpg')"/>
  <img src="/res/ardf/microcontroller.jpg" style="max-width: 100%;" onclick="onClick(this, '/res/ardf/microcontroller.jpg')"/>
</div>
</div>


