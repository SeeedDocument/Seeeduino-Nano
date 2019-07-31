---
name: Seeeduino Lotus Cortex-M0+
category: Arduino
bzurl: 
oldwikiname: 
prodimagename: Seeeduino_Lotus_Cover.jpg
surveyurl: https://www.surveymonkey.com/r/Seeeduino_Lotus
sku: 102010228
---

![](https://github.com/SeeedDocument/Seeeduino-Nano/raw/master/img/seeeduino-Nano-wiki.jpg)

The Seeeduino Nano is a compact board similar to the [Seeeduino V4.2](https://www.seeedstudio.com/Seeeduino-V4-2-p-2517.html)/Arduino UNO, and it is fully compatible with [Arduino Nano](https://store.arduino.cc/usa/arduino-nano) on pinout and sizes.


The same as Seeedunio V4.2, Seeeduino Nano is built around Atmega328P -- 8-bit AVR microcontroller. So you can use the same program code on both boards. However, the dimensions of the two are significantly different. Less than a quarter of the size, but with almost the same features, Seeeduino Nano will save more space for your project, more suitable for space-constrained scenes.

![](https://github.com/SeeedDocument/Seeeduino-Nano/raw/master/img/seeeduino-Nano-compare-2.jpg)


The Seeeduino Nano offers the same features and high-quality experience as the Arduino Nano in less than half the price. On the other hand, the Seeeduino Nano has also made the following improvements compared to the Arduino Nano. 1-Change the Mini-USB into Type-C, which is symmetrical and reversible. 2- Add one Grove I2C connector, with the help Grove system, you can play with hundreds of sensors and actuators simply by plugging.


One more thing, we know that only one on-board Grove connector may not be enough, so we made this [Grove shield for Arduino Nano](https://www.seeedstudio.com/Grove-Shield-for-Arduino-Nano-p-4112.html), which has 3 Grove digital connectors, 3 Grove analog connectors, 1 Grove I2C connector, and 1 Grove UART connector. 



<p style=":center"><a href="https://www.seeedstudio.com/Seeeduino-Nano-p-4111.html" target="_blank"><img src="https://github.com/SeeedDocument/wiki_english/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>






## Feature

- 43mm*18mm Tiny board
- 16M ATmega328P
- Fully compatible with Arduino Nano
- USB Type C for Programming and power
- On-board Grove I2C connector
- Breadboard-friendly



## Specification

|Item|Value|
|------------|-----------|
|Microcontroller|ATmega328P|
|Power Input|USB Type C|
|Operating Voltage|USB:5V|
|Digital I/O Pins|14|
|PWM Channels|6|
|Analog Input Channels|8|
|DC Current per I/O Pin|40 mA|
|IO Input Voltage|5V|
|SRAM|2 KB|
|Flash Memory|32KB|
|Maximum CPU frequency|16 MHz|



## Hardware Overview


<div align="center">
<figure>
  <p style=":center"><a href="https://raw.githubusercontent.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/master/img/Pin_out.jpg" target="_blank"><img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/Pin_out.jpg" /></a></p>
  <figcaption><b>Figure 2</b>. <i>Pinout, you can ckick the image to view the original file</i></figcaption>
</figure>
</div>







## Hardware Overview

The images below show an overview of Seeeduino Lotus hardware features. The pin-out and alternate functions of various pins of Seeeduino Lotus are shown in the pin-out diagram. This could be used as a quick reference.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/overview.jpg"/>
  <figcaption><b>Figure 3</b>. <i>Hardware Overview</i></figcaption>
</figure>
</div>





- **Grove Digital**  
There are 6 grove digital connectors, let's take **D3** for instance:  
>GND: System GND  
>VCC: Output 3.3V VCC  
>D3: Connect to digital pin 3  
>D2: Connect to digital pin 2  


You can find the silkscreen on the back of the board.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/4.jpg"/>
  <figcaption><b>Figure 4</b>. <i>Grove Digital Connectors</i></figcaption>
</figure>
</div>


- **Grove Analog**  
There are three analog Grove connectors, the input voltage range from 0~3.3V. If you need more than 3 analog input, you can use the analog pin in the header zone.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/5.jpg"/>
  <figcaption><b>Figure 5</b>. <i>Grove Analog Connectors</i></figcaption>
</figure>
</div>



- **Grove UART**  
We provide 3 hardware UART Port, one Grove UART, TX-RX pins in the header, and Multiplexed function pin **SCK** **SDO** in the SWD port. However the Multiplexed pin  is not supported by the firmware now.
So actually, only two hardware UART are available now.  **Serial** corresponds to Grove UART, and **Serial1** corresponds to RX-TX in the header zone.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/3.jpg"/>
  <figcaption><b>Figure 6</b>. <i>Grove Hardware UART</i></figcaption>
</figure>
</div>


- **Female Header**  
The Seeeduino Lotus Cortex-M0+ female header is fully compatible with Arduino UNO. It is worth mentioning that, in the DIGITAL part, all pins with a **~** in front support PWM output. Which means **D3,D4,D5,D6,D8,D9,D10,D11,D12,D13**, ten in total.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/2.jpg"/>
  <figcaption><b>Figure 7</b>. <i>Female Header</i></figcaption>
</figure>
</div>



- **Li-Po Header**  
You can use both USB and Li-Po battery supply for Seeeduino Lotus Cortex-M0+. Also, you can use this board to charge your Li-Po battery. When you power the board with USB and plug the Li-Po battery at the same time, the Li-Po battery will be charged, and the **CHR** LED will flash. After the battery is fully charged, the **CHR** LED will stop flashing.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/block/7.jpg"/>
  <figcaption><b>Figure 8</b>. <i>JST2.0 Li-Po Header</i></figcaption>
</figure>
</div>




## Getting Started


### Hardware

First of all, you need to:

* **Get a Micro-USB cable**
You need a Micro-USB cable first; the data cable of an Android Phone will do fine.
If you can't find one, you can buy one [here](http://www.seeedstudio.com/depot/Micro-USB-Cable-48cm-p-1475.html?cPath=98_100).

* **Connect the board**
Connect the Arduino board to your computer using the USB cable. The green power LED (labelled **PWR**) should go on.



### Software


- **Step 1. You need to Install an Arduino Software.**

[![](https://raw.githubusercontent.com/SeeedDocument/Seeeduino_Stalker_V3_1/master/images/Download_IDE.png)](https://www.arduino.cc/en/Main/Software)


**Launch the Arduino application**

Double-click the Arduino application (arduino.exe) you have previously downloaded.

!!!Note
    If the Arduino Software loads in a different language, you can change it in the preferences dialog. See the [Arduino Software (IDE) page](https://www.arduino.cc/en/Guide/Environment#languages) for details.


- **Step 2. Open the Blink example**  
Open the LED blink example sketch: **File > Examples >01.Basics > Blink**.


<div align="center">
<figure>
  <img src="https://raw.githubusercontent.com/SeeedDocument/Seeeduino_GPRS/master/img/select_blink.png"/>
  <figcaption><b>Figure 9</b>. <i>Blink Path</i></figcaption>
</figure>
</div>



- **Step 3. Add the Seeed Board**  
Please follow the [Seeed Board Intallation Guide](http://wiki.seeedstudio.com/Seeed_Arduino_Boards/) to add the Seeeduino Lotus Cortex-M0+ into your Arduino IDE.


<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/add_board.jpg"/>
  <figcaption><b>Figure 10</b>. <i>The key word is Lotus M0</i></figcaption>
</figure>
</div>




- **Step 4. Select your board and port**  
You'll need to select the entry in the **Tools > Board** menu that corresponds to your Arduino.
Selecting a **Seeeduino Lotus Cortex-M0+**.

<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/add_board_1.jpg"/>
  <figcaption><b>Figure 11</b>. <i>Choose the right board</i></figcaption>
</figure>
</div>


Select the serial device of the Arduino board from the Tools | Serial Port menu. This is likely to be COM3 or higher (**COM1** and **COM2** are usually reserved for hardware serial ports). To find out, you can disconnect your Arduino board and re-open the menu; the entry that disappears should be the Arduino board. Reconnect the board and select that serial port.

<div align="center">
<figure>
  <img src="https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/img/add_board_2.jpg"/>
  <figcaption><b>Figure 12</b>. <i>Choose the right port</i></figcaption>
</figure>
</div>


- **Step 5.Upload the program**  
Now, simply click the "Upload" button in the environment. Wait a few seconds and if the upload is successful, the message "Done uploading." will appear in the status bar.

<div align="center">
<figure>
  <img src="https://raw.githubusercontent.com/SeeedDocument/Seeeduino_GPRS/master/img/upload_image.png"/>
  <figcaption><b>Figure 13</b>. <i>Upload the code</i></figcaption>
</figure>
</div>


A few seconds after the upload finishes, you should see the pin 13 (L) LED on the board start to blink (in orange). If it does, congratulations! You've gotten Arduino up-and-running. If you have problems, please see the troubleshooting suggestions.


## Resources

- **[ZIP]** [Seeeduino Lotus Cortex-M0+ Eagle file](https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/res/Seeeduino_Lotus_Cortex-M0%2B.zip)
- **[PDF]** [SAM D21 DATASHEET](https://github.com/SeeedDocument/Seeeduino_Lotus_Cortex-M0-/raw/master/res/SAM_D21.pdf)



## Tech Support
Please submit any technical issue into our [forum](http://forum.seeedstudio.com/). 
<br /><p style="text-align:center"><a href="https://www.seeedstudio.com/act-4.html?utm_source=wiki&utm_medium=wikibanner&utm_campaign=newproducts" target="_blank"><img src="https://github.com/SeeedDocument/Wiki_Banner/raw/master/new_product.jpg" /></a></p>