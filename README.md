The TI99/4A was a great little computer.  
I fixed the keyboard - broken solder joints below the top row of keys. 
So far I have added 
Finagrom 99 - sd cartridge emulator 
32K memory upgrade + 3d printed case
dual joystick adaptor  + 3d printed case 
speech synthesizer - with 5V pass through to the 32kb mem. 

A few years ago I got hold of a Nicolette oscilloscope and 5.25" disk drive.   I was very excited, but on powering it on a cloud of white smoke escaped and I decided that perhaps oscilloscope maintenance was not for me.  also there was a mouses nest inside.  
The Oscilloscope was basically a Ti 9995 based computer,  CPU and lots of good IC's.  
So now what to do with a TMS9995 CPU ?  
I plan to build a breadboard 9995 computer according to plans by Stuart Conner
Then having proven the chips work I plan to move onto a Mini Cortex (also Stuart Conner).
if I can get that working then peraps I go for a KiCad replication of the original Cortex design and get some PCB's made ... ah dreams.  9 feb 2024

3/10/2024
I built the breadboard Cortex on 2 breadboards just like on the minicortex website.  despite multiple attempts to troubleshoot it will not boot for me.  and then I found that I'd labled the CPU wrong way up, and therefore put the CPU in backwards.  OoF.      

4/14/2024
The Mini Cortex is built ! using a board from Stuart Conner and a significant amount of help from Stuart I got it to boot. my biggest issue was getting the GAL22V10 programmed correctly, I cludged in a speaker and got it to play "bicycle made for two"..  

5/20/2024
I tried to build the breadboard Cortex again using solderable breadboards.  I learned that routing lots of wires is hard.  This second breadboard cortex does not work - I need to follow through troubleshooting each and every address line.   

6/6/2024
future goals - write some 16 bit assembly code. 
cludge in a 9918 video chip to the mini cortex and get it to do some graphics. 

