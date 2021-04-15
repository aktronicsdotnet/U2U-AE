# U2U-AE
USB to UART Based on CH340G for Arduino and ESP
<br> Description will be added soon...

<b>
What is U2U-AE?
</b><br>
Well U2U-AE is a simple USB to UART converter that allow you to program AVR and ESP MCUs really easily, for AVR you just need GND, RX and TX lines... sometimes DTR too (for auto reset). For ESP8266 you also need nRST and GPIO0 to put ESP8266 into the correct mood at the right time.(google esp8266 bare minimum for more info about the simplest way you can run ESP8266)
<br><br>

<b>
What is diffrent about U2U-AE?
</b><br>
Actually nothing is special about this board, with a little patience you can use any USB to UART board for serial cominucation but there are some advanges when you gather every feature on one single board...
<br>
-Uses cheap and readily avaible parts you can find in any country
<br>
-Small PCB with maximum uses of space (as much as possible)
<br>
-Fully documented and public knowlegde
<br>
-Compeletly free of charge for any type of use
<br>
-Fully compatible with most AVR and ESP MCUs and many more devices probably
<br>
-Work with both 3.3V and 5V MCUs
<br>
-Power can be provided via a sepereate micro usb port to avoid damages to your PC
<br>
-Fused power line for more protection
<br>
-Seperate LEDs for RX TX DTR and Power indication
<br>
-Can be easily adapted to USB-C connector or any other changes
<br><br>

<b>
Why is there two micro USB sockets?
</b><br>
It's just a precation... personaly I'm using a Surface Pro as my main computer at the moment, It's expensive and a pain in the rear to repair it so I put two Micro USB sockets so that power and data can be seperated from one another... Feel free to use 1 socket.
<br><br>

<b>
What are those jumpers for?
</b><br>
Well one set wich USB port is responsible for providing power to the board and the other one will set the VCC voltage into 3.3V or 5V. Note that the voltage of every logic pin will change according to the VCC too, so make sure you use the proper voltage otherwise if it's too low your MCU might not like it and if it's too high it't migh burn your MCU...
<br><br>

<b>
In a nutshell:
</b><br>
Is it perfect? Probably not. Does it do flipovers? Of cource not. Is it the best possible design? Far from it. But will it solve every need for a USB to UART? Most certainly will do!
<br><br>

<b>
How can I use this?
</b><br>
First you need to send the Gerber files from Gerber X2 folder to your fav PCB manufacturer and wait until they make the PCB for you and the you need to buy the neccesary components according to the bill of material and when everything arrvied careful solder them to the pcb and use it.

<b>
How hard is the soldering part?
</b><br>
Well I can tell you it's not for biginners... speically those Micro USB Ports are hard to solder by hands... (well not for me obviously!)
