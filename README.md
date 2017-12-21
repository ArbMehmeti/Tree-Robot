# Tree-Robot
Greatest Risk
-lasers not bouncing 
-chassis being too heavy to move
-very complicated mechanically 
Solve: 1) build it soon to find out if you can or not   2) come up with an alternative

Mechanical
-CNC mill base for wheels to latch into
-weld 3 (#)-leg chassis, innermost is tallest outermost is shortest(cone shape)
-3 boxes spread out with the lasers inside, push a button on top to fire the laser(figure out audience voting/interaction at later date)
-wooden base(strong to support the whole structure)
-3 layers(electronics bin, wheel grid, chassis/branches)

Electronics
-3 arduinos
-3 bluetooth chip
-3 heavier motors
-lots of wire
-3 light sensors
-castors and heavy wheels for each chassis

Software
-bluetooth control tree movements
-4 sequences

Power
-AA Batteries

Parts List
-3 laser pointers
-smoke machine- if we can get rotating mirrors for laser show
-15 casters
-chicken wire to make branches

Schedule
-make chassis (need access to metal working shop)
-make wooden base(need access to wood shop)
-make chassis rotate
-get lasers to hit sensors for Reine

Things to Ask Michael For
-access to metal and wood shops
-laser mirrors
-big motors

Manual Override
-Fake sensor input in Reine’s laptop

Videos
-https://www.youtube.com/watch?v=aBXPTNJytd0 
-https://www.youtube.com/watch?v=PZdzBk4Io54 (stepper motor bonus, optional)  https://www.youtube.com/watch?v=RzltkIU-hA0 


To Do
-talk with engineering student about schematic
-go to woodworking shop and mill base
-make metal chassis
-apply motors to chassis
-build branches
-install mirrors and sensors in branches
-make laser boxes and set up distances
-program branch positioning into bluefruit
-get mirrors on servos to make light show
-make our own wheels
-experiment with the batteries distribution




Priorities
1)Wood shop
2)Metal work

Tuesday 21/11/17
1.Base done
2.At least one chassis up and running 

Sunday 19/11/17
Build Wooden Base 





November 21, 2017

Outline of Program:

Modify Tito code:
Each button needs to be pressed at the same time. So each chassis will be controlled from a separate phone. The sensor will only be on one chassis.

Press Button 1 (1st chassis 10, 2nd chassis 20, 3rd chassis 30) - servo reaction on 1
Press Button 2 (1st chassis 30, 2nd chassis 20, 3rd chassis 10) - servo reaction on 2
Press Button 3 (1st chassis 20, 2nd chassis 10, 3rd chassis 30) - servo reaction on 3
Press Button 4 (1st chassis 10, 2nd chassis 30, 3rd chassis 20) - servo reaction on 2

Manual Overdrive:
This is on Reine’s end, and she will have control from her laptop on overriding any sensory information. Due to the difficulty of the wiring, our interaction may not make it into the end result of the project, we will see once the time comes.

Greatest Risk: 
The three Arduinos getting off time

Parts List
-laser mirrors
-3 arduinos
-3 bluetooth chips
-3 motors
-lots of wire
-3 light sensors
-castors and heavy wheels for each chassis
-aluminum for chassis
-wooden base
-3 battery packs


First I wanted to build a tree shaped robot. The robot would have mirrors in its branches that would reflect lasers like a robot DJ. As I later found out the first idea was very difficult to be accomplished so I redesigned the robot by giving him one spinning chassis and a box of mirrors reflecting lasers. Then I decided to put LED on the tracks of the base. The project had several Arduinos. Two of them are used to power the LED. The other one to rotate the mirrors inside the box. The Arduinos were positioned in order to have an even weight distribution. To rotate the box, I used a simple motor and for the mirrors I used two DC motors. A wooden shaft was installed to keep the box from tilting. The balance of the box was one of the major issues I had in the process of building the robot. The dimensions of the box were 30x15 so balancing it was not easy. I should have tested the balance of the box with the added weight as well. For the sequences of the LED we used Arduino to write two different codes so the sequences of the LED were different. We uploaded the codes on the separated Arduino’s which were both powered by 4 AA batteries each. The mirrors in the box were powered by a single AA battery and an Arduino in which I wrote a code to slow down the rotation of the mirrors so they don’t fall off. That was also a difficulty because the motors rotated so fast the box lost balance. I had to slow the rotation down and glue the motors in wooden platform in order for the rotation not to affect the balance. Another challenged that I faced was mounting the mirrors on the right position so the reflection of the lasers create shapes. Until the last moment this was a major concern. If I have the chance to do another task like this, I would do the testing earlier so I don’t have to worry about things failing in the last minutes.
