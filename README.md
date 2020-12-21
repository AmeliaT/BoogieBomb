# BoogieBomb
Remix of Fornite Boogie Bomb by The Ray Gun Project www.theraygunproject.com
Original project + files: https://www.thingiverse.com/thing:2801202

I updated CAD files, components, the audio file, & the code.

My remix used most of the original CAD files from "The Ray Gun Project" with two exceptions:
The "BB-Core" & the "BB-Core_ButtonCover" were remodeled to account for different components. 
I printed the files in black, white, gold, and grey/silver, per the original instructions. 

I used the following components:
Adafruit Feather M0 Express : https://www.adafruit.com/product/3403
Adafruit Prop-Maker FeatherWing: https://www.adafruit.com/product/3988
Headers: https://www.adafruit.com/product/2886
On-Off Power Button / Pushbutton Toggle Switch: https://www.adafruit.com/product/1683
Lithium Ion Polymer Battery - 3.7v 350mAh: https://www.adafruit.com/product/2750

Thin Plastic Speaker w/Wires - 8 ohm 0.25W: https://www.adafruit.com/product/1891
Molex Pico Blade 2-pin Cable - 200mm: https://www.adafruit.com/product/3922

NeoPixels (I used 2 x 16 pixel strips of the 144/m variety for a total of 32 pixels)
JST PH 3-pin Plug Cable: https://www.adafruit.com/product/4336

MicroSwitch: https://www.amazon.com/URBESTAC-Momentary-Hinge-Roller-Switches/dp/B00MFRMFS6/ref=sr_1_3?ie=UTF8&qid=1519328212&sr=8-3&keywords=micro+switch
Lynch Pin: https://www.homedepot.com/p/Everbilt-3-16-in-x-1-1-2-in-Zinc-Plated-Lynch-Pin-815528/204276207

I pulled a cleaner audio file and have included the wave file needed to run the code.

I developed the code in CircuitPython, with thanks to Adafruit folks & thea.codes.

Lessons learned...
I should have gone with the Adafruit Feather M4 Express board and the Short Feather Headers, though the headers would require a core redesign. 
The Feather M4 Express would have allowed me to choose from some different options for the LEDs.
