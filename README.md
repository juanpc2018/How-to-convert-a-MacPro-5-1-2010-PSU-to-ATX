# How to convert a MacPro 5,1 2010 PSU to ATX

Why?
because PSU fail, there was 2 brands Delta and other, same as PowerMac G5
but the Newer 5,1 PSU is different, more compact.

IF you can find a New replacement, that´s the easy option.

Original MacPro 5,1 (2010) [PSU](https://en.wikipedia.org/wiki/Power_supply_unit_(computer)) is [80 Plus Platinum](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) "Better than Gold",
and is smaller than standard ATX of the same power rating 900w

replacing with an [standard ATX PSU](https://en.wikipedia.org/wiki/ATX#Power_supply) is possible but complex...
is better to replace with a [SFF "Small Form Factor"](https://en.wikipedia.org/wiki/Small_form_factor_PC) PSU, and Modular "cables can be removed".
becuase the PSU Fan is Not on the PSU, its on the Case / Chassis,
Mac Pro 5,1 case has a compartment and an a metallic grid that holds the fan,
separates the DVD area on the front on the case, from the PSU area on the Back, 
if want to fit an standard size ATX PSU
requires to remove the metallic grid that holds the 120mm 12v DC fan. 
very difficult to do, without large metallic cutters, drill or pliers to cut the bolts.
requires to remove the CPU tray and Main board to avid any matallic dust falling on the electronics.

2nd problem is DVD drives, need to be removed permanently and the plastic spring mechanism inside the case that holds the 2 front doors,
the reason is to move the fan from the "center" of the upper compartment, to the front, because the PSU needs the air flow.
upper compartment and lower compartment are separated by a large metallic wall.

inside the front of the case has metallic rails that can hold the 120mm fan very easy, fits very nice.
but there is another problem: the cable of the fan is under the main board, 
you need to remove the board completely to remove the cable, 
the case has 2x small square holes on the front, between the upper and lower compartments,
where the fan cable can go much nicer, but those holes need to be widened a bit more for the 2x VGA 6+2-pin cables.
if wnat to run both VGA cables from the upper chamber to the lower, 1 hole is difficult.

i´ve tried to remove the 120mm Fan cable without removing the board, Not recommended, it could damage something on the back of the board.

also requires to cut the PSU cables from the original PSU, or buy a damaged Mac PSU and cut the cables, 
and also cut the cables from the New ATX / SFF PSU,
can buy extra / replacement cables for your New PSU, but some china manufacturers change desing of the PSU cables in the middle of production,
the same PSU cables may Not be compatible, you need a PSU tester, or a DMM "Digital Multi Meter".

The Original PSU has a custom connector required,
that connector is behind an aluminium panel, behind the DVD drives, easy to remove.
connects the PSU to the Mainboard.

The only problem with this modification is the 2x PSU temperature sensors inside the PSU
maybe can be emulated with 2x 20K-50K resistors connected to 5v Stand-By rail.
or the original temperature sensor module can be removed from the original PSU, and used stand alone.

The 120mm PSU fan is the only "Normal" fan on the case.

There is also another minor problem with the 5v Rail, may require a low voltage drop diode, when connecting the 5v Stand.By to the 5v Rail.

in the following days will upload photos of the cable...



