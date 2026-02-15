# Coolermaster-USB-C-remix

USB-C daughterboard for Cooler Master NovaTouch keyboards

Manufacturers are charging a large setup fee for assembly of the [original version](https://github.com/davek184/CoolerMasterUsbC) along with tariffs, generally prefer the original version, but remixing for a more affordable option.

![Render](/assets/photoFinal.jpg)

Parts
-----
- USB-C breakout board *(female)* [Amazon](https://www.amazon.com/dp/B09WCSF8FC?psc=1&ref_=cm_sw_r_cp_ud_ct_GT8ZEJJ0JSE9TSRHDTRX), [Adafruit](https://www.adafruit.com/product/5180)
- 5.1 Ohm resistor *(package size: 0402 (or prefered 0805, solder: surface)*
- JST PH cable *(wires: 5, length: 150mm)* [Amazon](https://www.amazon.com/dp/B0BKSNJGQL?psc=1&ref_=cm_sw_r_cp_ud_ct_QFTQSGYQR8YCQEH24Z3N), [Adafruit](https://www.adafruit.com/product/5089) 
- 3d printed bracket

Tools
-----
- Soldering iron
- Multimeter
- Hot glue gun
- 3d printer (or order from online service)

3d Print Bracket
-----
Cooler Master NovaTouch
- [Bracket with access hole (recommended)](/3d/coolermaster-novatouch-usbc-bracket-accessHole.stl)
- [Bracket without access hole](/3d/coolermaster-novatouch-usbc-bracket.stl)
Printing
- Orientation: Vertical
- Brim: Full or Mouse Ear
- Material: PETG *suggested*

[TinkerCad design](https://www.tinkercad.com/things/gupjL9dNZFy-coolermaster-usb-c-bracket?sharecode=hrGqW4dKQAlAj4FP0EM5Q-o44ddQxqJ0IT2FK_grpPk)

Assembly 
-----
- Solder cable to beakout board (Skip shield wire or combine it with ground)
- Solder 5.1 ohm resistor if USB C to C cable compatibility desired (this is not an trivial solder job).  [Similar solder details](https://electronics.stackexchange.com/questions/595590/jrc-b008-for-usb-c-microcontroller-power-supply/601047#601047)
- Test cable with multimeter to ensure there are no shorts!
- Test cable with keyboard
- Push daughterboard into 3d print (use a flat head screwdriver and and the access hold in the bottom for alighnment). Dry fit to ensure in a good position.  
- Hot glue breakout board to 3d printed brac
- Install in keyboard

Wiring
----
- Shield (Yellow)
- D- (White)
- D+ (Green)
- GND (Black)
- 5V (Red)

Note: Other Cooler master keyboards may have a different pinnout

Notes
----
- Norbatouch has a different 3d printed part but same general instructions
- Soldering 5.1 ohm resistor is not the easiest thing to do recommend buying a board that already has it installed
