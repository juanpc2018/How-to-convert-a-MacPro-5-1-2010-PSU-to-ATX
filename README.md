# How to convert a MacPro 5,1 2010 PSU to ATX

Why?
because PSU fail, there was 2 brands Delta and other, same as PowerMac G5
but the 5,1 PSU is different, more compact.

Original MacPro 5,1 (2010) PSU is [80 Plus Platinum](https://en.wikipedia.org/wiki/80_Plus#Efficiency_level_certifications) "Better than Gold",
and is smaller than standard ATX of the same power rating 900w

replacing with a [standard ATX PSU](https://en.wikipedia.org/wiki/ATX#Power_supply) is possible but complex...
is better to replace with a SFF "Small Form Factor" PSU,
becuase the PSU Fan is Not on the PSU, its on the Case / Chassis,
The Mac Pro 5,1 case has a compartment and an a metallic grid that holds the fan,
separates the DVD area on the front from the PSU area on the Back, 
if want to fit inside an standard size ATX PSU
requires to remove the metallic grid that holds the 120mm 12v DC fan. 
very difficult to do, without large metallic cutters, drill or pliers to cut the bolts.
requires to remove the CPU tray and Main board to avid any matallic dust falling on the electronics.

2nd problem is DVD drives, need to be removed and the plastic spring mechanism inside that holds the 2 front doors,
the reason is to move the fan from the "center" of the upper compartment area, to the front, because it needs the air flow.
upper compartment and lower compartment are separated by a large metallic wall.

inside the front of the case has some metallic rails that holds the 120mm fan very easy, fits very nice.
but there is another problem, the cable of the fan is under the main board, 
you need to remove the board to remove the cable, the case has small holes on the front where the cable can go much better.
i´ve tried to remove the cable without removing the board, Not recommended, it could damage something on the back of the board.

also requires to cut the PSU cables from the original PSU, it has a custom connector to the board,
that connector is behind an aluminium panel, behind the DVD drives, easy to remove.

The only problem with this modification is the 2x PSU temperature sensors, inside the PSU
maybe can be emulated with 2 resistors connected to 5v Stand-By rail.



