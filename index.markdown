---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# 3D printer that prints solid, 100% dense, precise, and strong metal objects.


![The Atomwell Printer](/assets/img/printer.jpg)

**Specs:**
 - 3D Printing process: Selective Powder Deposition (SPD)
 - Build volume of Model C: about 279x274x110 mm
 - Build volume of Model G: about 610x610x310 mm
 - Pourer diameter: 0.9 mm and 1.9 mm
 - Layer height: 0.1 to 1 mm (user configurable in GUI)
 - Min width of a detail: one pourer diameter
 - Min height of a detail: one layer height
 - Model C cost: $7,000 + shipping
 - Model G cost: $35,000 + shipping



# [The Shop](https://shop.atomwell.com/)


# FAQ
**What metals are supported?**

The printer itself is material agnostic, and can pour any powder that flows though a small hole. In theory, SPD can work with any metal combinations where the infill metal has lower melting temperature than the powder. But different metals require different baking conditions. [In theory](https://en.wikipedia.org/wiki/Ellingham_diagram), for [not-very-reactive metals](https://en.wikipedia.org/wiki/Reactivity_series), such as iron, copper, nickel, tin, lead, molybdenum, cobalt, tungsten, palladium, cadmium, silver, gold, platinum - you can use coke (carbon) as a flux. Same goes for tungsten carbide, boron carbide, and silicon carbide. Other carbides and nitrites might work as well. So far, we have tried carbon steel, brass, bronze, copper-iron, and copper-nickel. Reactive metals, such as chromium, vanadium, aluminum, magnesium, titanium, and others might be baked in an atmosphere with high H2/H2O ratio, or high CO/CO2 ratio, according to Ellingham diagram. Also, using the pot technique, the requirements for the atmosphere for the infill metal are more relaxed than for the powders, because when the pot is tilted, the infill flows and infills the powder in a few seconds, so it doesn't have much time to oxidize. So, for example, we could infill copper powder with aluminum alloys in a pottery kiln with added hydrogen or propane atmosphere, with appropriate safety procedures. This way we could economically 3D print in aluminum bronze.



**What's the shrinkage?**

There is no shrinkage. The metal powder is not sintered, but infused with infill metal. So, the size and shape are preserved.



**What's the tensile strength?**

SPD doesn't reduce the strength in any way. The metal microstructure is identical to the casting. So the strength of the printed objects is determined by the type and quality of metals you put in. Several independent labs shared their analysis.



**What's the print time?**

Print time very much depends on the size and complexity of the object. Rough average would be about 24 hours.



**Is there any post-processing required?**

Yes. After filling the crucible with the powders, you would need to bake it in a kiln or furnace.



**What's the baking temperature?**

The baking temperature must be in-between melting temperatures of the infill metal and the build powder.



**What's the baking hold time?**

The hold time should be sufficient for the heat to get to the middle of the crucible and melt the infill metal. The minimum hold time depends on the size and thermal conductivity of the crucible, the mass, and the difference between the melting temperature of the infill metal and your baking temperature. Usually 2 or 3 hours is sufficient.



**What kind of kiln is required?**

For copper infill metal, your kiln should be able to go above the copper melting temperature, which is 1084°C, so most pottery kilns would work. A kiln with programmable digital controller is preferred, because it can be programmed to warm up slowly, to avoid cracking the crucible. A new pottery kiln might cost you about $1000. A used one you might find for a few hundred dollars on Craig's List, if you look for a while.



**How can I buy the printer?**

You can order the printer by email.



**Where can I buy the consumables? (metal powders, support powders, infill metal, and crucibles)**

You can buy the consumables from 3rd parties. In general, for the powder to flow good, the hole should be at least 10 times larger than the particle size. So, for example, 200 microns powder would flow well thru 2 mm or larger hole. And 40 microns powder would flow well thru 0.6 mm or larger hole. Powders smaller than 40 microns are not recommended, because they tend to cake, and also they get airborne easier, which would present a health hazard. So, the ideal particle size is 40 microns or larger. The powders and the infill metal shouldn't have too many impurities. For example, reactive metals, especially in the powder, might oxidize and prevent wetting. The crucible should be non-porous, and obviously, should be able to withstand the baking temperature. From MetalShipper you can buy zinc and copper infill. Other things form atomwell.com and TriDPrinting.com.



**What are the practical applications for SPD?**

There are many:
 - Molds and mold cores (for plastic injection molding) with conformal cooling channels.
 - Rocket engines, including injector plates, pumps, combustion chambers, and nozzles.
 - Large ship propellers in nickel aluminum bronze.
