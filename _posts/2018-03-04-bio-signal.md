---
title: EMG Muscle Therapy Device
layout: post 
---

This project has been developed together with the NGO "A chance for children"
who are helping children in Uganda. Some of the children have injured muscles
and need to slowly start practicing moving their arms again.

The goal for this project was to create a device supporting these children in their
recovery by developing a device which can measure muscle contraction using
electrodes and detecting the small electric signal (electromyography).
The device then sets a contraction pattern as the goal and gives the user
feedback on how well they are doing in achieving it.

The software is running on a Raspberry Pi version 2 and is created in C using
the GTK+ framework to create a graphical user interface accessible via touchscreen.
The muscle signal is going through an electronic amplifier, read by a Cypress
PSoC microcontroller and then sent to the Raspberry Pi via UART for display.

Code and [documentation](https://github.com/simonkaufmann/EMG-muscle-therapy-device/blob/master/manual/manual_emg_muscle_therapy_device.pdf) can be found on [Github](https://github.com/simonkaufmann/EMG-muscle-therapy-device)

<div class="w3-row-padding">
<div class="w3-half">
  <img src="/res/biosignal/setup.png" style="max-width: 100%;" onclick="onClick(this, '/res/biosignal/setup.png')"/>
  <img src="/res/biosignal/software1.png" style="max-width: 100%;" onclick="onClick(this, '/res/biosignal/software1.png')"/>
  <img src="/res/biosignal/software2.png" style="max-width: 100%;" onclick="onClick(this, '/res/biosignal/software2.png')"/>
</div>

<div class="w3-half">
  <img src="/res/biosignal/attached.png" style="max-width: 100%;" onclick="onClick(this, '/res/biosignal/attached.png')"/>
  <img src="/res/biosignal/labels.png" style="max-width: 100%;" onclick="onClick(this, '/res/biosignal/labels.png')"/>
</div>
</div>


