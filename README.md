# How to convert a MacPro 5,1 2010 PSU to ATX

Why? </br>
because [PSU fail](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)#Life_span) </br>
there was 2 brands Delta and other, same as PowerMac G5 </br>
but the 5,1 PSU is different, more compact. </br>

IF you can find a New replacement, that´s the easy option. </br>

Original MacPro 5,1 (2010) [PSU](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)) is [80 Plus Platinum](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) "Better than Gold", </br>
and is smaller than standard ATX of the same power rating 900w </br>

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
may require to remove the original AC IEC Connector from the PSU, and create an Extension cable, cuting a power cable and solder to the Original power connector, </br>
another problem is holding the original power connector to the case without PSU. </br>
the "easy" option is to run a standard power cable insde the case, through the square hole on the back. </br>

Fitting a New ATX SFF-L PSU inside the Original PSU case/shell, maybe possible. </br>
as you can see there are many ways to do the mod, </br>
i did the lazy method, nothing fancy, just works. </br>
