# How to convert a MacPro 5,1 2010 PSU to ATX

Why?
because PSU fail, there was 2 brands Delta and other, same as PowerMac G5
but the Newer 5,1 PSU is different, more compact.

IF you can find a New replacement, that´s the easy option.

Original MacPro 5,1 (2010) [PSU](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)) is [80 Plus Platinum](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) "Better than Gold",
and is smaller than standard ATX of the same power rating 900w

IF you replace with 80 Plus Titanium PSU, Efficiency will increase, and power consumption will lower -20w iddle, and -40w-50w when under GPU load. 
IF you replace with 80 Plus Gold PSU, Efficiency will lower, and power consumption will increase +20w from Platinum, and +40w from Titanium Idle.

replacing with an [standard ATX PSU](https://en.wikipedia.org/wiki/ATX#Power_supply) is possible but complex...
is better to replace with a [SFF "Small Form Factor"](https://en.wikipedia.org/wiki/Small_form_factor_PC) PSU, and Modular "cables can be removed".
because the PSU Fan is Not on the PSU, its on the Case / Chassis,
There was many years ago a [Fanless SFF-L PSU](https://www.youtube.com/watch?v=gnkaMFQ14TU&t=25s) may work.. without removing the Fan grill, but the problem is runing the cables to the lower chamber.
the only way is on the bottom wall.

[SilverStonetek](https://www.silverstonetek.com/en/product/power-supplies/?filter=SFX_SFXL) has nice SFF-L models.

Mac Pro 5,1 case has a compartment and an a metallic grid that holds the fan,
separates the DVD area on the front of the case, from the PSU area on the Back, 
if want to fit an standard size ATX PSU
requires to remove the metallic grid that holds the 120mm 12v DC fan. 
or placing the PSU on the front where the DVDs are,
removing the PSU Fan Grill is very difficult to do, without large metallic cutters, drill or pliers to cut the bolts.
requires to remove the CPU tray and Mainboard to avod any matallic dust falling on the electronics.
Case is made from Aluminum, can be washed later with a garden hose.

DVD drives, need to be removed permanently and the plastic spring mechanism inside the case that holds the 2 front doors,
the reason is to move the fan from the "center" of the upper compartment, to the front, because the PSU needs the air flow or will over heat.
upper compartment and lower compartment are separated by a large metallic wall, bnottom airflow does Not affect upper airflow.

inside the front of the case has metallic rails that can hold the 120mm fan very easy, fits nice.
but there is another problem: the cable of the PSU fan is under the main board, 
requires to remove the mainboard completely to remove the PSU fan  cable, 

the case has 2x small square holes on the front, between the upper and lower compartments,
where the fan cable & VGA cables can go nice, but those holes need to be widened 
if wnat to run 2x VGA 6+2-pin cables from the upper chamber to the lower in 1 hole, is difficult.

i´ve tried to remove the 120mm Fan cable without removing the board, Not recommended, it could damage something on the back of the board.

also requires to cut the cables from the original PSU, or buy a damaged Mac PSU and cut the cables, 
also cut the cables from the New ATX / SFF PSU to join both,
to buy extra / replacement cables for the New PSU is an option, but some china manufacturers change desing of the PSU cables in the middle of production,
the same PSU cables may Not be compatible with the PSU, need a PSU tester & a DMM "Digital Multi Meter".

The Original PSU has a custom connector required,
that connector is behind an aluminium panel, behind the DVD drives, easy to remove.
connects the PSU to the Mainboard.

The only problem with this modification is the 2x PSU temperature sensors inside the PSU
maybe can be emulated with 2x 20K-50K resistors connected to 5v Stand-By rail.
or the original temperature sensor module can be removed from the original PSU, and used stand alone.
or use 2x real 56k thermal resistors, sold by many PC cooling manufacturers like Koolance, etc...
10K may Not work, tests needed.

The 120mm PSU fan is the only "Normal" fan on the case.

There is also other minor problem with the 5v Rail,
may require a low voltage drop diode, when connecting the 5v Stand-By to the 5v Rail.
or the HD 5770 fan will spin turned-off, Not a Big deal, 
to turn-off the PSU from a switch is better anyway, PSUs consume energy "Turned-Off" in Standy-By mode.

in the following days will upload photos of the cable...



