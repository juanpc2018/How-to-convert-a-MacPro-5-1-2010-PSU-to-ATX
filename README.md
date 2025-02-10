# How to convert a MacPro 5,1 2010 PSU to ATX

Why? </br>
because [PSU fail](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)#Life_span) </br>
there was 2 brands Delta and other, same as PowerMac G5 </br>
but the 5,1 PSU is different, more compact. </br>

IF you can find a New replacement, that´s the easy option. </br>

Original MacPro 5,1 (2010) [PSU](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)) is [80 Plus Platinum](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) "Better than Gold", </br>
and smaller vs. standard ATX PSU of the same power rating 900w </br>

IF you replace with 80 Plus Titanium PSU, Efficiency will increase, & power consumption will lower -20w idle, and -40w-50w under load. </br>
IF you replace with 80 Plus Gold PSU, Efficiency will lower, & power consumption will increase +20w from Platinum, and +40w from Titanium Idle. </br>

replacing with an [standard ATX PSU](https://en.wikipedia.org/wiki/ATX#Power_supply) is possible but complex... </br>
is better to replace with a [SFF "Small Form Factor"](https://en.wikipedia.org/wiki/Small_form_factor_PC) Modular PSU "cables can be removed". </br>
because the PSU Fan is Not on the PSU, its on the Case / Chassis, </br>
There was many years ago a [Fanless SFF-L PSU](https://www.youtube.com/watch?v=gnkaMFQ14TU&t=25s) may work.. without removing the Fan grill, but the problem is runing the cables to the lower chamber. </br>
the only way is on the bottom wall. </br>

[SilverStonetek](https://www.silverstonetek.com/en/product/power-supplies/?filter=SFX_SFXL) has nice SFF-L models. </br>

Mac Pro 5,1 case has a compartment and an a metallic grid that holds the fan, </br>
separates the DVD area on the front of the case, from the PSU area on the Back,  </br>
if want to fit an standard size ATX PSU </br>
requires to remove the metallic grid that holds the 120mm 12v DC fan.  </br>
or placing the PSU on the front where the DVDs are, </br>
removing the Fan Grid/Grill is very difficult without large metallic cutters, drill & pliers to cut the bolts. </br>
requires to remove the CPU tray and Mainboard to avod any matallic dust falling on the electronics. </br>
Case is made from Aluminum, can be washed later with a garden hose. </br>

DVD drives need to be removed permanently and the plastic spring mechanism inside the case that holds the 2 front doors, </br>
the reason is to move the fan from the "center" of the upper compartment to the <--front, because the PSU needs the air flow. </br>
upper compartment and lower compartment are separated by a large metallic wall, bottom airflow does Not affect upper airflow. </br>

inside the front of the case has metallic rails that can hold the 120mm fan very easy, fits nice. </br>
but there is another problem: the cable of the PSU fan is under the main board,  </br>
requires to remove the mainboard completely to remove the PSU fan cable,  </br>
the fan cable is very long, connects to the front of the Board. </br>

the case has 2x small square holes on the front, between the upper and lower compartments, </br>
where the fan cable & VGA cables can go nice, but those holes need to be widened  </br>
if wnat to run 2x VGA 6+2-pin cables from the upper chamber to the lower in 1 hole, is difficult. </br>

i´ve tried to remove the 120mm Fan cable without removing the board, Not recommended, it could damage something on the back of the board. </br>

also requires to cut the cables from the original PSU, or buy a damaged Mac PSU and cut the cables,  </br>
also cut the cables from the New ATX / SFF PSU to join both, </br>
to buy extra / replacement cables for the New PSU is an option, but some china manufacturers change desing of the PSU cables in the middle of production, </br>
the same PSU cables may Not be compatible with the PSU, need a PSU tester & a DMM "Digital Multi Meter". </br>

The Original PSU has a custom connector required, </br>
that connector is behind an aluminium panel, behind the DVD drives, easy to remove. </br>
connects the PSU to the Mainboard. </br>

The only problem with this modification is the 2x PSU temperature sensors inside the PSU </br>
maybe can be emulated with 2x 20K-50K resistors connected to 5v Stand-By rail. </br>
or the original temperature sensor module can be removed from the original PSU, and used stand alone. </br>
or use 2x real 56k thermal resistors, sold by many PC cooling manufacturers like Koolance, etc... </br>
10K may Not work, tests needed. </br>

The 120mm PSU fan is the only "Normal" fan on the case. </br>

There is also other minor problem with the 5v Rail, </br>
may require a low voltage drop diode, when connecting the 5v Stand-By to the 5v Rail. </br>
or the HD 5770 fan will spin turned-off, Not a Big deal,  </br>
turn-off the PSU from a switch is better, PSUs consume energy "Turned-Off" in Standy-By mode. </br>

in the following days will upload photos... </br>

another problem is the [AC IEC power connector](https://en.wikipedia.org/wiki/IEC_60320#C13/C14_coupler) the Original PSU is Centered on the case, </br>
all ATX PSUs have the power connector somewere else,  </br>
may require to remove the AC IEC Connector from the original PSU, and create an Extension cable, cuting a power cable and solder to the Original power connector, </br>
or more fancy, removing the New AC connector, and solder the extension directly </br>
another problem is holding the original power connector to the case without PSU. </br>
the "easy" option is to run a standard power cable insde the case, directly to the New ATX PSU through the square hole on the back. </br>

Fitting a New ATX SFF-L PSU board inside the Original PSU case/shell, maybe possible. </br>
as you can see there are many ways to do the mod, </br>
i did the lazy method, nothing fancy, just works, looks like Frankenstein. </br>

# at your own risk

Pinouts of: </br>
24-pin ATX12V 2.x power supply connector </br>
viewed from the PSU connector, plastic tab on the right </br>
or from the back of the ATX extension connector cable, plastic tab on the right --|--> Apple MacPro 5,1 2010 Power Connector</br>
Apple connector can only fit 1-way because it has 2 asymetric notches, Top Left | Center Right. </br>
Not complete!

I used a 24-Pin ATX v2 Extension cable, and cut it in half, </br>
soldered the Mac Power Connector cables to ATX Extension cable cut in half, </br>
that allows to disconnect the PSU and use it on another PC or a PSU tester. </br>

```
┌────────────────┐
│ 1─[X] │ 13─[Orange +3.3v]                         
│ 2─[X] │ 14─[X]                                    ╔═══╗ ╔═══╗                     ╔═══╗ ╔═══╗
│ 3─[ ]─┼─15─[ ]──>                                 ╚╗G ╠═╣+12║                     ║+12╠═╣GND║
│ 4─[ ] │ 16─[Green PowerOn]                     ═╗ ║│N│║ ║│ │║   ┌──┬──┬──┬──┬──┐  ║│ │║ ║│ │║ ╔═
│ 5─[ ]─┼─17─[ ]──>                               ║ ║│D│║ ║│ │║   [○][○][○][○][○]   ║│ │║ ║│ │║ ║
│ 6─[ ] │ 18─[ ]                                  ║ ║   ║ ║   ║   [○][○][○][○][○]   ║   ║ ║  ╔╝ ║
│ 7─[ ] │ 19─[ ]───────┬───>                      ║ ║│ │║ ║│ │║   [○][○][○][○][○]   ║│ │║ ║│ │║ ║
│ 8─[X] │ 20─[X]       │                         ═╝ ║│ │║ ║│ │║   └──┴──┴──┴──┴──┘  ║│ │║ ║│ │║ ╚═
│ 9─[ ]───21─[ ]       │                            ║GND╠═╣+12║                     ║+12╠═╣GND║
│10─[X] │ 22─[ ]       │                            ╚═══╝ ╚═══╝                     ╚═══╝ ╚═══╝
│11─[X] │ 23─[X]       │                              
│12─[X] │ 24─[ ]───────┘                              
└────────────────┘

[9] Purple +5 VSB PSU standby + [21] +5vdc, Joined, Not connected to Mac.
The +5VSB supply is used to provide the soft-power feature of ATX when a PC is turned off,
as well as powering the real-time clock to conserve the CMOS battery.
standby supplies power even when the rest of the supply wire lines are off. 
This can be used to power the circuitry that controls the soft-power-on signal.
Problem is that the Mac PSU does Not have a dedicated +5VSB line, its all +5V.
i joined the +5VSB "never-off" to a a Single Rail +5V on the PSU, to power all +5V lines when Off, as test.
works but the HD 5770 fan spins when turned-off, need better pin-point of the +5VSb.

[13]─Orange +3.3v connected to Mac-[L○]
[3]+[15] Joined Ground connected to Mac.
[4] +5V connected to Mac. | [16] PowerOn Green connected to Mac.
[5]+[17] Joined Ground connected to Mac.
[6] +5V connected to Mac.
[7]+[18] Joined Ground connected to Mac.
[19]+[24] Joined Ground connected to Mac.
[22] +5V connected to Mac.

┌───┬────┬────┬────┬───┐ 
[A○]│[B○]│[C○]│[D○]│[X]│
[F○]│[G○]│[H○]│[I○]│[X]│
│[X]│[L○]│[M○]│[N○]│[X]│
└───┴────┴────┴────┴───┘

[A○] -> [7]+[18] GND. | [B○] -> [16] PowerOn Green | [C○] -> [19]+[24] GND. | [D○] -> [5]+[17] GND. |
[F○] -> Thermistor-1 | [G○] -> Thermistor-2 | [H○] -> [4]+5V | [I○] -> [3]+[15] GND. |
[L○] -> [13]─Orange +3.3v PSU | [M○] -> [22] +5V | [N○] -> [6]+5V |

The +12V on each side has 2 wires +12v, 2-wires GND on each side.
requires 2-VGA connectors, 1x for each side...
each PCIe requires 75w, Front Rear Turbo & PSU Fans require Watts.
CPU requires Watts, SouthBridge ICH9R requires power.
Modular PSUs VGA connector is 8-pin, but output cable is 6+2
Only 3-pins have Power, all other VGA pins are Ground or Sense "feedback".
Each VGA connector has: 3x +12v | 3x GND,
Mac Connector requires: 2x +12v | 2x GND.
Mac +12v/GND AWG Size is Fatter vs. Original EVGA T2 VGA cables, 1 or 2 AWG numbers less.

[H○] -> [4] +5V
[M○] -> [22] +5V
[N○] -> [6] +5V

i have connected:
ATX [9] Purple +5VSB standby -> ATX [21] +5vdc
because its a single +5v Rail PSU, when in-Standby / PowerOFF,
sends +5VSB to all +5V ATX outs: [H○]+[M○]+[N○]
but thats Not the best way to do it,
The proper way is to connect a Low Voltage Drop Diode to +5VSB in series,
disconnect [9] Purple from ATX [21],
and connect to only One: [H○] or [M○] or [N○],
One is the Mac +5VSB, Not All.

[F○] -> Thermistor-1
[G○] -> Thermistor-2
That´s a mistery...
could be connected to each other pin with a 20K-50K resistor between.
could be connected to a 20K-50K resistor each or a 20K-50K-100K potentiometer centered, center pin to +5VSB.
directly to +5V does Not work.
to 2x True 56K thermistors: 1-pin to Mac 1 pin to GND each,
or 1x 56K thermistor, connected between [Fo] & [Go]

```
[AWG Chart](https://www.powerstream.com/Wire_Size.htm)
VGA (6+2)-pin PCIe is "opposite" of CPU (4+4) </br>
VGA (6+2)-pin PCIe has +12V on the pins far away from the plastic tab </br>
CPU (4+4)-pin has +12V on the pins closer to the plastic tab. </br>

This modification can be done both ways... </br>
cutting CPU PSU cables or cutting VGA cables, </br>
i recommend cutting VGA PSU cables. </br>
CPU cables can be disconected on EVGA T2. </br>
