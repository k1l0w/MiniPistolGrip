# MiniPistolGrip

*Description:* Re-imagining of the awesome Hoyt Esk8 remote to have a pistol grip and a larger battery.  You have to remove (desolder) the POT from the hoyt board and create a separate PCB to make the remote mounted trigger assembly. That is the only way I could figure out how to package this they way that I wanted.  See Freesk8 post for more pictures. Right now there is a wide grip version that fits both 21700 and stock hoyt battery. I can add the narrow grip that only fits the stock version later. 
https://forum.freesk8.org/t/mini-pistol-grip-with-remote-trigger-assembly/849/1

Many thanks to the Freesk8 crew to inspiring me to work on this and giving me the great starting point with the 3D models. Lots of fun to learn fusion and 3D printing. 

*Trigger Assembly:*  You can create this by using copper clad PCB material and drilling the hole pattern shown in the pdf. Or you can fabricate the PCB yourself with the gerbers attached.  The assembly uses the Hoyt trigger parts that come with the remote:  Spring, thumb wheel (maybe create your own with a trigger), key nob(?) and bracket that limits the range of motion and holds it all together. You have to de-solder the POT from the Hoyt board and mount it to the PCB.  Solder wires between the trigger PCB and the hoyt board.  Wires should face out on this assembly or the spring might hit them.  Make sure to secure the wires to the main PCB, pads rip off PCBs easily. Maybe with hot glue?  The 3D models were sourced from the FreeSk8 model repository. The tigger assembly STL is attached for additional modeling you might want to do.  Maybe design your own shell with a remote mounted trigger?  

*Files in repository* 

-STLs (self tapping and embedded nuts): STLs have two versions of securing the lid to the grip body.  One with imperial machine screws size 2-56, length 7/16”, qty 6 and 4 low profile nuts that are embedded into the print (with a pause around 5.7mm height).  The other with 6 10mm m2.5 self tapping screws. 

-hole pattern PDF for making your own PCB with copper clad Fr4 or something similar.  I made the first one with a bridgeport.  Dimensions in inches.

-Trigger PCB gerbers [TiggerPCB1_2_23_2021.zip]

**NEW**
-MiniPistolGrip R11.f3z  Fusion archive of the full model.  This is the version with the trigger guard.  Warning: I have not finished printing this and verifying fit.

-MiniPistolGripGaurd STL files for both self tapping screws and embedded nuts.  

*Printing
-I printed these with the interior face down.  In my experience his results in the best surface finish for the spots you will touch.  I used supports and printed on a Prusa MK3s.

*Assembly:* 
1)Slide the trigger assembly into the grip body. You might need to file the sides of the trigger slot so the trigger moves clean and freely.
2)Put the two side screws in to hold down the trigger assembly. 
3) Slide battery in, Use so foam or neoprene so they don't rattle around. 
4) fold the wire down
5) Four screws to attach the lid and two screws to secure the trigger assembly.  



 

Things to do:
-Removable trigger gaurd
-Flashlight Mount


