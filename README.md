### sugarshieldXL
##### case for shieldXL + PiSugar S plus

<img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/1.jpg width=400> <img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/2.jpg width=400>

This is a case I designed for my shieldXL to add an internal battery. I had a couple of requirements: use the original shieldXL faceplate, add lots of extra cooling for the warm-running Raspberry Pi 4, and integrate the PiSugar S plus battery with as little increase in size as possible.

This project is **heavily** influenced by <a href=https://github.com/JGuzak/shieldXl_battery>jordo's ShieldXL battery case</a>. 

### Parts required

* assembled <a href=[https://github.com/okyeron/shieldXL](https://www.denki-oto.com/store/p98/shieldXL_%28DIY_norns_synthesizer_kit%29.html#/)>shieldXL</a>, full kit with standoffs and acrylic/PCB top panel
* <a href=https://github.com/PiSugar/PiSugar/wiki/PiSugarS-Plus>PiSugar S Plus battery<a>
* 3D printed housing, either <a href=https://github.com/roge-rm/sugarshieldXL/blob/main/stl/sugarshieldxl-1.0.stl>with</a> or <a href=https://github.com/roge-rm/sugarshieldXL/blob/main/stl/sugarshieldxl-1.0-noswitch.stl>without</a> external switch
* 1 x JST-PH 2.0 female header (or pigtail)
* 4 x m2.5x16mm bolts
* 1 x micro slide rocker switch, 2 pole/3 pin (part SS12F15VG5)
* 2 x m1.4 or m1.7 stainless screws (to mount switch)
* hookup wire to attach external switch

### Assembly

<img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/5.jpg width=600>

1. Print the housing in 0.3mm layer height or finer, any material you desire. <br>You can choose either the version <a href=https://github.com/roge-rm/sugarshieldXL/blob/main/stl/sugarshieldxl-1.0.stl>with<a/> an external switch or one <a href=https://github.com/roge-rm/sugarshieldXL/blob/main/stl/sugarshieldxl-1.0-noswitch.stl>without</a>.
2. Remove the magnets from the PiSugar board and battery. Do whatever you want with them (don't eat them).
3. Attach the JST-PH female connector to the PiSugar board, respecting the correct polarity. If using the standalone header instead of a pigtail I suggest you hold it down with some hot glue or something.
4. If you're using an external switch you'll want to solder two hookup wires to the CTRL and OFF pads on the PiSugar S board. See <https://github.com/PiSugar/PiSugar/wiki/PiSugarS-Plus>their wiki</a> for pictures if you need clarity.
5. Attach the PiSugar board to the back of the Raspberry Pi in a way that will hold it together until you can screw it in place inside the case. Two sided tape should work for this. <br>If you're really _brave_ (stupid) and you _bravely_ broke off one or more of the pogo pins.. you can knock the rest off and solder the PiSugar board to the Raspberry Pi directly. _You're so brave_ (not stupid).

<img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/3.jpg width=600>

5. If you're using a female header instead of a pigtail you'll want to mount the battery as shown ahead of assembly. Two sided tape can be used to hold it in place against the backs of the audio ports. I'd also suggest a piece of tape in the housing where the battery will go.<br>If you used a proper pigtail you can just tape the battery down in the case near the front corner, under where the display will be.
6. Slide the whole assembly into the housing at an angle, back end (audio ports) first. There is a cutout in the top of case, on the right side, that will allow the 3.5mm MIDI ports to fit. Magically feed the wires for the external switch through first/at the same time while also holding the battery in place and making sure it makes it to its home under the display. I find it easier to do this whole step upside down (turn the shieldXL assembly and housing upside down, not yourself).
7. Attach the board to the bottom of the case with the m2.5x16mm bolts and thread the original faceplate standoff in the top right corner into place. 

<img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/4.jpg width=600>

8. Solder the two hookup wires to the middle and one outer pole of the micro slide switch - this side of the switch is the **off** position.
9. Mount the switch in the mounting position on the right side of the case using the 2 m1.4 srews.
10. Install the faceplate using the screws provided with the shieldXL kit.
11. Turn the little white power switch on the PiSugar board to the **on** position (slid towards the front of the housing), then you can use the external power switch to power the unit on.
12. You're done!

<img src=https://raw.githubusercontent.com/roge-rm/sugarshieldXL/main/pictures/6.jpg width=600>
