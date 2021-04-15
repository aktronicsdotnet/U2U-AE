# U2U-AE
USB to UART Based on CH340G for Arduino and ESP
<br> Description will be added soon...

<b>
What is U2U-AE?
</b><br>
Well U2U-AE is a simple USB to UART converter that allow you to program AVR and ESP MCUs really easily, for AVR you just need GND, RX and TX lines... sometimes DTR too (for auto reset). For ESP8266 you also need nRST and GPIO0 to put ESP8266 into the correct mood at the right time. (google esp8266 bare minimum for more info about the simplest way you can run ESP8266)
<br><br>

<b>
What is different about U2U-AE?
</b><br>
Actually nothing is special about this board, with a little patience you can use any USB to UART board for serial communication but there are some advantages when you gather every feature on one single board...
<br>
-Uses cheap and readily available parts you can find in any country
<br>
-Small PCB with maximum uses of space (as much as possible)
<br>
-Fully documented and public knowledge
<br>
-Completely free of charge for any type of use
<br>
-Fully compatible with most AVR and ESP MCUs and many more devices probably
<br>
-Work with both 3.3V and 5V MCUs
<br>
-Power can be provided via a separate micro USB port to avoid damages to your PC
<br>
-Fused power line for more protection
<br>
-Separate LEDs for RX TX DTR and Power indication
<br>
-Can be easily adapted to USB-C connector or any other changes
<br><br>

<b>
Why is there two MICRO USB sockets?
</b><br>
It's just a precaution... personally I'm using a really expensive computer at the moment which is also a pain in the rear to repair it so I put two Micro USB sockets so that power and data can be separated from one another... Feel free to use 1 socket.
<br><br>

<b>
What are those jumpers for?
</b><br>
Well one set which USB port is responsible for providing power to the board and the other one will set the VCC voltage into 3.3V or 5V. Note that the voltage of every logic pin will change according to the VCC too, so make sure you use the proper voltage otherwise if it's too low your MCU might not like it and if it's too high it might burn your MCU...
<br><br>

<b>
In a nutshell:
</b><br>
Is it perfect? Probably not. Does it do flip overs? Of course not. Is it the best possible design? Far from it. But will it solve every need for a USB to UART? Most certainly will do!
<br><br>

<b>
How can I use this?
</b><br>
First you need to send the Gerber files from Gerber X2 folder to your fav PCB manufacturer and wait until they make the PCB for you and the you need to buy the necessary components according to the bill of material and when everything arrived careful solder them to the PCB and use it.
<br><br>

<b>
How hard is the soldering part?
</b><br>
Well I can tell you it's not for beginners... specially those Micro USB Ports are hard to solder by hands... (well not for me obviously!)
<br><br>

<b>
For more advanced users...
</b><br>
For more advanced users, I've left the original design so you can change anything you want. This board was designed by Altium Designer V20.
<br><br>

<b>
How can you find me?
</b><br>
I've left my Instagram on this GitHub just in case you needed to contact me for any reason...
<br><br>
