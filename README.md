# tec-CPLD-BG
tec1 CPLD addon using epm3064atc44

Ben Grimmett
1Scteptfem1bper f25m9 0soat9 e6:4mc6 Pd1M  · 
Altera (Intel) epm3064 CPLD, 3.3v regulator, decoupling caps, DIP 28 footprint. 6 pin jtag header. 
All 5v tolerant IO. 3.3v logic is compatible with 5v logic. 
64 logic elements in this little thing. Consider a LE a latch or a register or a gate.  64 LEs can make 64bits of ram, or a 64bit counter, or 64 bit adder/subtractor/ spi port, DAC, PWM, just about anything you could do with a handfull of 74 series chips all in one DIP. 
You could build a video card with a couple of these, some ram and an EPROM. Or a serial port, keyboard controller, configurable address decoder / mapper etc. 
Erase and rewrite code to these at least 1000 times.
Smd fully assembled. 28 and 6 pin header included but not soldered. 
$13.50ea. Or $8ea unassembled kit. 


Altera
A$0
Posted 2 weeks ago
Details
Altera (Intel) epm3064 CPLD, 3.3v regulator, decoupling caps, DIP 28 footprint. 6 pin jtag header. 

All 5v tolerant IO. 3.3v logic is compatible with 5v logic. 

64 logic elements in this little thing. Consider a LE a latch or a register or a gate.  64 LEs can make 64bits of ram, or a 64bit counter, or 64 bit adder/subtractor/ spi port, DAC, PWM, just about anything you could do with a handfull of 74 series chips all in one DIP. 

You could build a video card with a couple of these, some ram and an EPROM. Or a serial port, keyboard controller, configurable address decoder / mapper etc. 

Erase and rewrite code to these at least 1000 times.

Smd fully assembled. 28 and 6 pin header included but not soldered. 

$13.50ea. Or $8ea unassembled kit. 

Mark Jelic Ingmar Meins
Seller Information
Ben Grimmett
TEC-1 Z80 Computer Group
Joined Facebook in 2007
25 Comments
Mark Jelic
Yes please. I’ll give it a crack. 😃
 · Reply · Share · 2w
Reinoud de Lange
How do you program it?
 · Reply · Share · 2w
Ben Grimmett
Reinoud de Lange Using a USB Blaster from eBay ($4 china, $7 local for us aussues)
 · Reply · Share · 2w
Reinoud de Lange
Ben Grimmett Did you make that board?
 · Reply · Share · 2w
Scott Gregory
I’ll grab a couple of unassembled ones please.😊
These have an oscillator too?… See More
 · Reply · Share · 2w
Ben Grimmett
Scott Gregory That sounds awesome! probably stick with the drag n drop schematic editor though as HDL could be a bit of a distraction
 · Reply · Share · 2w
Scott Gregory
Yep. That works. You have the pinout/schematic available of these boards?
 · Reply · Share · 2w
Ben Grimmett
I do but it looks very confusing! I'll draw something simple up now
 · Reply · Share · 2w
Ben Grimmett
Hard mode schematic
No photo description available.
 · Reply · Share · 2w
Scott Gregory
Um yep. lol
 · Reply · Share · 2w
Scott Gregory
Esentially a 27Cxx pinout. 14 and 28 as Vss and Vcc and a JTAG header.
 · Reply · Share · 2w
Ben Grimmett
thats a bit better.
May be an image of text that says '42 43 44 2 3 5 6 8 10 12 13 14 15 GND VCC 35 34 33 31 28 27 25 23 22 21 20 19 18 TDI TCK TMS GND 3.3 TDO'
 · Reply · Share · 2w
Ben Grimmett
Step1: Start a new project, select MAX3000 family, EPM3064ATC44-10
 · Reply · Share · 2w
Ben Grimmett
No photo description available.
 · Reply · Share · 2w
Ben Grimmett
Step2. Right click, insert symbol, find what you want to insert. Can be simple gates, or you can look in megafunnctions for the 74 series chips. Just click and place where you want
 · Reply · Share · 2w
Ben Grimmett
No photo description available.
 · Reply · Share · 2w
Ben Grimmett
Step3. Wire it together, add input and output pins.
No photo description available.
 · Reply · Share · 2w
Ben Grimmett
Save, and click the Play button. It'll compile your design into code, show you how many IO pins you've used, and how many logic elements you've used
 · Reply · Share · 2w
Ben Grimmett
No photo description available.
 · Reply · Share · 2w
Ben Grimmett
Step5. Click on Pin planner, then drag and drop the pin names to the physical pins on the chip. If you named your signals in the schematic, it makes it much easier. You can place them where ever you like. I've only used IO pins in the CPLDip
 · Reply · Share · 2w
Ben Grimmett
May be an image of floor plan
 · Reply · Share · 2w
Ben Grimmett
Hit compile again, and now you're ready to put your code onto the CPLD. Use the programmer icon, connect your usb blaster, click program. It'll be finished in 2 seconds and you're ready to use your custom IC
 · Reply · Share · 2w
Ben Grimmett
No photo description available.
 · Reply · Share · 2w
Reinoud de Lange
When you put it like that it almost sounds easy... 🙂
 · Reply · Share · 2w
Scott Gregory
Reinoud de Lange Once you get your head around it, it isn't hard at all. I learned VHDL (the hardware description language) first as I was doing a complex device first up. Ben was a huge help with that.
