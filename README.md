# Wooden Ambika Enclosure

![](https://waterpigs.co.uk/img/2018-05-15-ambika.jpeg)

This repo contains most of the files necessary to build a wooden, optionally laser engraved case for the Mutable Instruments [Ambika](https://mutable-instruments.net/archive/ambika/build/) polyphonic symthesizer.

## Files

The plans were orignally drawn in Eazydraw for Mac, and the original Eazydraw file is given here. Ambika Enclosure Plans 720 x 520.svg contains the exact same data in SVG format. EazyDraw generally does a very good job of exporting organised SVG files, so the various layers and objects should be easy enough to make changes to in other vector drawing applications.

Each individual part is exported in its own SVG file, with the bound size given in mm in the filename, allowing you to make sure it’s correctly scaled when imported into your vector drawing or CAM applications.

## Parts and Design

The finished case consists of three main parts, designed to be cut out of walnut blanks on a CNC router.

* The main body of the case, which is made up of the following sub-parts, glued together:
    * The front panel, optionally laser-engraved with graphics
   * The lowered square into which the encoder gets screwed, glued into the recess on the underside of the front panel
    * The acrylic display window, fitted and glued into the front panel
    * The three 8mm thick side panels, which get glued together, and to the top panel. The panel with ventilation slots should go on the left side near the power regulators
* The back panel with all the holes for connectors, back-mounted volume control, and power switch. This is held in place by both the audio output nuts and four M2 screws which secure it to the 8mm sides.
* The bottom panel which fits into the recess created by the side panels. I chose to make this out of 4mm clear Acrylic so it’s possible to see into the synth. This is secured by the various M3 standoffs, and some M2 screws which connect it to the sides of the case.

The case is designed for metal-shafted pots and encoders with M9 threaded bushings, which get screwed onto the front panel. If for some reason you really want to fit your expensive, labour-intensive Ambika with flimsy plastic pots and encoder, the pot holes can be reduced to 7mm in diameter, and the lowered sub-panel for the encoder can be left out.

I chose to fit a wired volume pot to the back of the synth, to leave the front panel looking cleaner. This can easily be changed by adding a holes for the volume pot in the front panel. Again, this is an exercise left to the reader.

I cut the button holes for custom made buttons. If you want to use store-brought plastic buttons then you’ll probably have to adapt the size of the holes to fit.

Once you’ve imported the SVG files into your CAM application of choice, it’s up to you to make sure all the graphics are scaled and cuts are configured correctly. Most outside cuts should be outside outline. The only inside cut which doesn’t remove all the material is the display cut, which should be configured as an inside outline cut.

You’ll probably have to manually change the cut depths of all the shaded areas to match your materials. Study the assembly plans and adjust accordingly to make sure everything will fit together correctly.

## Assembly

Finish building the Ambika and PCBs first. Solder headers on the power and volume switch connection points, and solder a wired power switch and volume pot to matching connectors.

Prepare the wood blanks, and cut out the parts. If you’re going to laser engrave the front, I would recommend grain raising and sanding the surface to 400 grit before laser engraving, then continuing to sand to higher grits afterwards.

Glue the front panel to the sides, then trim excess and sand everything. Provisionarily screw the Ambika to the front panel and glue the lowered encoder place in the right position.

Cut out the other parts, fit and finish them all. Once the main case is finished (oiled, varnished or whatever), glue the acrylic display window in place.

Assemble the Ambika. You’ll need to drill 1.5mm pilot holes for the various M2 screws securing the wooden parts of the case. The mechanical assembly is similar to the official version documented on the Mutable Instruments archive, with the addition of two 10mm M3 hex standoffs between the motherboard PCB and the main case, along the top of the instrument. These are to provide extra stability along the back edge where the main case is not secured to the connector panel.