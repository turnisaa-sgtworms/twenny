twenny, 20 key wireless split.

![pretty collage of twenny](https://github.com/turnisaa-sgtworms/twenny/blob/main/images/twenny-collage.png)

features: 
 - diodeless
 - reversible
 - throughole soldered xiao
 - cheap! fits jlcpcb's 2 dollar pcb requirements... good even for the tariffs we're getting right now in the US.
 - two 3dp case options, one with a cut acrylic top
 - easy (but mildly jank, fine as long as you follow instructions) assembly. just solder on a xiao and switches and you're good to go!

**IF YOU DO NOT READ THE BUILD GUIDE THIS THING WILL PROBABLY EXPLODE!!!!! READ IT!!!!!**

# bill of materials

2x - twenny pcb

2x - seeed xiao nrf52840 dev boards

20x - choc v1 switches of choice

20x - choc v1 keycaps of choice

2x - adafruit lipo 100mAh battery - product id 1570 (both cases are designed to use this battery)

2x - female jst connector

**For the new case:**

1x (of each) - 3d printed case parts

*optional based on your bottom case choice*: 12x - 2mm thick, 3.5mm outer diameter m.2 heat inserts

*also optional*: 12x - 2mm thick, 3.5mm outer diameter m.2 heat inserts

12x - 5mm m.2 screws

**For the old case:**

1x (of each) - 3d printed case parts

2x - cut acrylic, somewhere between 1 and 2 mm thick

12x - 2mm thick, 3.5mm outer diameter m.2 heat inserts

8x - 5mm m.2 screws

4x - 14mm m.2 screws


# quick guide, INCOMPLETE probably, will add pics eventually:

**1 THE HARD PART:**

       you may want to do this after part two, read all the steps then decide for yourself 
       which direction you want to take.
  
       you will need to solder the female jst connectors to the battery pads on the bottom 
       of each xiao. NOTE! that many jst connectors may be backwards, so if the wires do not 
       match the wires on your battery when plugged in you should be able to unclip them
       and swap them so that they do.
  
       mock up the final build so you can trim your jst connectors to fit as well as possible. 
       i probably could have cut mine shorter, but that's fine.
  
       solder em on! the pads are small and close together so be sure they will not short, 
       and be sure they will not block the pin headers!
  
**2 THE JANK PART - SUPER IMPORTANT!!:**

       clip the pin headers included with your xiao so you 
       have the following lengths (for each board!):
  
             1x - 4 pins long
    
             1x - 5 pins long
    
             5x - 1 pin long
    
       remove the plastic bits from 3 of the 1 pin bits, **SAVE THE PLASTIC!** 
       the metal pin piece for these three can be tossed.
  
       solder the headers on so that:
  
             on the left side, from top to bottom you have 
             1 pin, 1 space, then 5 pins soldered.
    
             on the right side, from top to bottom you have 
             1 space, 1 pin, 1 more space, and then 4 pins soldered.
    
       ADD THE EXTRA PLASTIC TO THE TOP AND BOTTOM PINS ON THE LEFT, 
       AND THE MIDDLE PIN ON THE RIGHT! THE EXTRA HEIGHT IS NECESSARY!
  
       ensure all the pins are straight by mocking it all together 
       with the pcb when you solder the pins to the dev board.
  
**3 THE EASY PART:**

       once you have the jst connector and pin headers soldered 
       to the dev board, solder it onto the pcb!
       note that 3 pins will be UNPOPULATED! the board is completely 
       reversible as long as you follow the steps above.
  
       now, feel free to solder your choc switches of choice onto the board.
  
**4 THE HOT PART (IS THIS GAG STILL FUNNY?):**

       set your soldering iron to just above the melting temp of
       whatever you printed your case in, i think i did about 10C over.
  
       choose a tip that you can poke into the heat inserts and it 
       will kind of pick them up, without protruding too far through them.
  
       use pliers or something along those lines to put each heat insert 
       onto the soldering iron, then push them into each of the heat insert 
       holes till they are flush. you may want a damp paper towel to cool 
       and flatten the plastic once they are placed 
       (or just burn your thumb a little if youre kinda dumb like me)
  
       there should be 4 heat insert holes on the top face of 
       each half (two on each piece) and 2 on the inside of
       the bottom part of each half.
    
**5 THE EASY PART AGAIN:**

       screw each case half together with 14mm m.2 screws through 
       the top part of each half into the heat inserts on the inside of 
       the bottom part of each half. leave these loose till later.
  
       install your battery in the gap in each case, 
       install your pcb on top of it.
  
       slip the acrylic piece on top, and screw the 5mm 
       m.2 screws into the heat inserts through the holes in it. 
       leave em loose till you have them all started, then 
       tighten the bottom screws, then tighten the top screws down evenly.
  
**6 THE FIRM PART:**

       flash some firmware on that bad boy!
  
       note: you will need a bind for SOFT OFF. this keeb 
       shas no physical off switch, but soft off works great.
    
