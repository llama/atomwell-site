---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Home
layout: home
---

# 3D printer that prints solid, 100% dense, precise, and strong metal objects.


![The Atomwell Printer](/assets/img/printer alpha.png)

**Specs:**
 - 3D Printing process: Selective Powder Deposition (SPD)
 - Build volume of [Model C](https://shop.atomwell.com/products/atomwell-model-c-printer): about 279x274x110 mm
 - Build volume of [Model G](https://shop.atomwell.com/products/atomwell-model-g-printer): about 610x610x310 mm
 - Pourer diameter: 0.9 mm and 1.9 mm
 - Layer height: 0.1 to 1 mm (user configurable in GUI)
 - Min width of a detail: one pourer diameter
 - Min height of a detail: one layer height


# [The Shop](https://shop.atomwell.com/)


# FAQ
## What metals are supported?

The printer itself is material agnostic, and can pour any powder that flows though a small hole. In theory, SPD works with any metal combination where the infill metal has lower melting temperature than the powder. But different metals require different baking conditions. [In theory](https://en.wikipedia.org/wiki/Ellingham_diagram), for [not-very-reactive metals](https://en.wikipedia.org/wiki/Reactivity_series), such as iron, copper, nickel, tin, lead, molybdenum, cobalt, tungsten, palladium, cadmium, silver, gold, platinum - you can use coke (carbon) as a flux. Same goes for tungsten carbide, boron carbide, and silicon carbide. Other carbides and nitrites might work as well. So far, we have tried [carbon steel](https://docs.google.com/spreadsheets/d/1InG5o_eR3Z1hYlxJB3COUeOonhFEBPlwYaCg1Lemv4Q/edit?usp=sharing>), [brass](https://docs.google.com/spreadsheets/d/18NCpYvJ4JaTn_vihkoSAjU3ODrVvq1mPrt4nNHfykZE/edit?usp=sharing), bronze, copper-iron, and [copper-nickel](https://docs.google.com/spreadsheets/d/1wGesWI6_bRnYGpHiXtUsIiW4QXO45Ab6jgjt0TzkKvU/edit?usp=sharing). Reactive metals, such as chromium, vanadium, aluminum, magnesium, titanium, and others might be baked in an atmosphere with high H2/H2O ratio, or high CO/CO2 ratio, according to [Ellingham diagram](ttp://web.mit.edu/2.813/www/readings/Ellingham_diagrams.pdf). Also, using the pot technique, the requirements for the atmosphere for the infill metal are more relaxed than for the powders, because when the pot is tilted, the infill flows and infills the powder in a few seconds, so it doesn't have much time to oxidize. So, for example, we could infill copper powder with aluminum alloys in a pottery kiln with added hydrogen or propane atmosphere, with appropriate safety procedures. This way we could economically 3D print in [aluminum bronze](ttps://www.copper.org/publications/newsletters/innovations/2002/08/aluminum_bronze.pdf).



## What's the shrinkage?

There is no shrinkage. The metal powder is not sintered, but infused with infill metal. So, the size and shape are preserved.



## What's the tensile strength?

SPD doesn't reduce the strength in any way. The metal microstructure is identical to the casting. So the strength of the printed objects is determined by the type and quality of metals you put in. Several independent labs shared their [analysis](https://drive.google.com/open?id=10Pq88kBZLvNwrTfFW9AO5eOt8JnsLkd4).



## What's the print time?

Print time very much depends on the size and complexity of the object. Rough average is about 24 hours.



## Is there any post-processing required?

Yes, but much less than with other metal printing technolgies. After filling the crucible with the powders, you would need to bake it in a kiln or furnace. After baking, the part needs to be snipped off of the sprue. This part is usable as-is in many applications–it is fully dense and has no supports to remove.



## What's the baking temperature?

The baking temperature must be in between melting temperatures of the infill metal and the build powder.



## What's the baking hold time?

The hold time should be sufficient for the heat to get to the middle of the crucible and melt the infill metal. The minimum hold time depends on the size and thermal conductivity of the crucible, the mass, and the difference between the melting temperature of the infill metal and your baking temperature. Usually 2 or 3 hours is sufficient.



## What kind of kiln is required?

For copper infill metal, your kiln should be able to go above the copper melting temperature, which is 1084°C, so most pottery kilns would work. A kiln with programmable digital controller is preferred, because it can be programmed to warm up slowly, to avoid cracking the crucible. A new pottery kiln might cost you about $1000. A used one you might find for a few hundred dollars on Craig's List, if you look for a while.



## How can I buy the printer?

You can order the printer in he [Atomwell Shop](https://shop.atomwell.com)



## Where can I buy the consumables? (metal powders, support powders, infill metal, and crucibles)

The [Atomwell Shop](https://shop.atomwell.com). We are working to acquire and supply high quality, tested stock of all materials you might want to use with your SPD printer. Many of these materials are made custom for us.

You can also buy consumables from 3rd parties. In general, for the powder to flow well, the hole should be at least 10 times larger than the particle size. So, for example, 200 micron powder would flow well through a 2 mm or larger hole. And 40 microns powder would flow well through a 0.6 mm or larger hole. Powders smaller than 40 microns are not recommended, because they tend to cake, and also they get airborn easier, which would present a health hazard. So, the ideal particle size is 40 microns or larger. The powders and the infill metal shouldn't have too many impurities. For example, reactive metals, especially in the powder, might oxidize and prevent wetting. The crucible should be non-porous, and obviously, should be able to withstand the baking temperature. From MetalShipper you can buy [zinc](https://www.metalshipper.com/zinc.html) and [copper](https://www.metalshipper.com/copper-chop.html) infill. [TriDPrinting.com](TriDPrinting.com) may also have some useful materials.



## What are the practical applications for SPD?

There are many:
 - Molds and mold cores (for plastic injection molding) with [conformal cooling channels](https://www.google.com/search?q=conformal+cooling+channels&client=ubuntu&hl=en&sxsrf=ALeKk00GumPqh0f0ofqcKaueSphStd-npA:1583881270059&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjc997DgZHoAhWhoFsKHX4pCLkQ_AUoAXoECA4QAw&biw=1920&bih=1008).
 - [Rocket engines](https://www.google.com/search?q=3d+printed+rocket+engines&tbm=isch&ved=2ahUKEwja3LLFgZHoAhX8IzQIHV5eAS8Q2-cCegQIABAA&oq=3d+printed+rocket+engine&gs_l=img.1.0.35i39j0l2j0i8i30j0i24.1120054.1123217..1123660...0.0..0.110.397.2j2......0....1..gws-wiz-img.......0i131j0i67.17KuG2yDdYE&ei=ORxoXprcH_zH0PEP3ryF-AI&bih=1008&biw=1920&client=ubuntu&hl=en), including injector plates, pumps, combustion chambers, and nozzles.
 - Large ship propellers in [nickel aluminum bronze](https://www.copper.org/applications/marine/nickel_al_bronze/pub-222-nickel-al-bronze-guide-engineers.pdf).


## I have another question.

[Email us!](mailto:contact@atomwell.com)