FirePower^x Ruleset/To Do
---------------------------

Version : 0.1

Author : Mark S. Webb

Source : https://github.com/MarkStefanWebb/Pinball1

Topic : https://pinside.com/pinball/forum/topic/trying-to-revive-an-old-em-dealer-s-choice-with-opp-and-mpf

Pinball : FIREPOWER, Williams 1980

        4 players EM, 2 flippers, 4 bumpers, 1 Outlane Ball Save ,8 Standups, 2 Sling Shots, 
        10 rollovers, 10 standup targets, 1 spinner, 3 ball locks, Multi-ball,
        a row of 10 lights playfield-centered between flippers, 3 Big Bonus, 4 Multipliers 

Comments: this is a first draft, need to be coded and adjusted !


The game will Start in Attract Mode, cycling through Last Score, High Score, and Free Play Screens.... 
PRESS the START BUTTON!

Advancing past the Attract Display, a carousel will open showing the list of possible Games to load. 
Firma - FirePower based on Orignal Rules
Ignited - FirePower based on Deluxe Rules
Redux - FirePower a new rule set look at Comibnation Shots
Exploration - FirePower Opens with a "Dark" deep space playfield.... unlocking scoring with first hit events. 


---------------------------
Firma. CLASSICAL RULES
---------------------------
This ruleset is active by default and corresponds mostly to the initial rules, except the skill shot and ball save
3 balls played by each player
***************
***Ball save*** :
***************

        During 10 sec, ball is given back as a ball saver

[ ] Done and uploaded to github

**********
**INGAME**
**********

*************************
***Single shots values*** :
*************************

[x] unlit [ ] lit 01: Upper Eject Hole (1000/10000 lit)
[x] unlit [ ] lit 02: "F" Rollover (1000)
[x] unlit [ ] lit 03: lit "I" Rollover (1000)
[x] unlit [ ] lit 04: "R" Rollover (1000)
[x] unlit [ ] lit 05: "E" Rollover (1000)
[x] unlit [ ] lit 06: Top Center Target (1000)
[x] unlit [ ] lit 07: Top Left Stand Up  (50)
[x] unlit [ ] lit 08: FirePower Bonus Lights
[x] unlit [ ] lit 09: Top Right Standup (50)
[x] unlit [ ] lit 10: Bottom Left Jet/Pop Bumper (100/1000 lit)
[x] unlit [ ] lit 11: Bottom Left Jet/Pop Bumper (100/1000 lit)
[x] unlit [ ] lit 12: Bottom Left Jet/Pop Bumper (100/1000 lit)
[x] unlit [ ] lit 13: Bottom Left Jet/Pop Bumper (100/1000 lit)
[x] unlit [ ] lit 14: Spinner (100/1000 lit)
[x] unlit [ ] lit 15: Right Eject Hole (1000/10000 lit)
[x] unlit [ ] lit 16: Right Eject Rollover (1000)
[x] unlit [ ] lit 17: Middle Left Standup (50)
[x] unlit [ ] lit 18: "FIRE" Light
[x] unlit [ ] lit 19: "POWER" Light
[x] unlit [ ] lit 20: "1" Target (1000)
[x] unlit [ ] lit 21: "2" Target (1000)
[x] unlit [ ] lit 22: "3" Target (1000)
[x] unlit [ ] lit 23: "4" Target (1000)
[x] unlit [ ] lit 24: "5" Target (1000)
[x] unlit [ ] lit 25: "6" Target (1000)
[x] unlit [ ] lit 26: Middle Right Standup (50)
[x] unlit [ ] lit 27: Left Eject Hole (1000/10000 lit)
[x] unlit [ ] lit 28: Left Eject Rollover (1000)
[x] unlit [ ] lit 29: Top Power Target "P" (1000)
[x] unlit [ ] lit 30: Middle Power Target "O" (1000)
[x] unlit [ ] lit 31: Bottom Power Target "W" (1000)
[x] unlit [ ] lit 32: Lower Right Standup (50)
[x] unlit [ ] lit 33: Left Inside Rollover (1000/3000 lit)
[x] unlit [ ] lit 34: Right Inside Rollover (1000/3000 lit)
[x] unlit [ ] lit 35: Left Kicker (10)
[x] unlit [ ] lit 36: Right Kicker (10)
[x] unlit [ ] lit 37: Left Outside Rollover (1000)
[x] unlit [ ] lit 38: Left Ball Save Kicker
[x] unlit [ ] lit 39: Right Outside Rollover (1000)
[x] unlit [ ] lit 40: Left Flipper (Carousel Selector)
[x] unlit [ ] lit 41: Right Flipper ("FIRE" Lane Changer, Carousel Selector)



[ ] Done and uploaded to github (except slingshots scoring that i forgot)

***************************
***Group shot completion*** :
***************************

- "FIRE" Rollover : 

        [ ]1. Rolling Over Lights "FIRE" and advance Bonus

        [ ]2. Complete "FIRE" lights Fire Light and advance Bonus Multiplier
		
- Targets 1-6: 
        
        [ ]1. Hit Targets advance Bonus

        [ ]2. Complete Either Bank turns on Ball Save Kicker

        [ ]3. Complete Both Banks lights Spinner and 2 Jet/Pop Bumpers(10 and 12)

        [ ]4. Complete Both Banks second time Lights Remaining Jet Pop Bumpers

        [ ]5a. Complete Both Banks Lights Ejector Holes. 

        [ ]5b. Bottom Ejector holes will lock... Top will kick until first two locked. 

        [ ]5c. Complete Banks second time and on turns on one hole at at time. 

- "Power" Targets:

        [ ]1. Complete Bank scores 10000 ,Lights Power, Lights Inside Rollovers

        [ ]2. Hitting Center "Power" Target awards Extra ball when Lit. 

- Eject Holes:

        [ ]1. Advance Bonus

        [ ]2. Lock Balls for Multiball

- Inside Rollovers

        [ ]1. Advance Bonus

- Outside Rollovers

        [ ]1. Advance Bonus

        [ ]2. Special Lights for FIRE POWER bonus four times.

- FIRE POWER Bonus
        
        [ ]1. 10000, 30000, 50000 light up 

        [ ]2. Outlanes Light up for Special. 

- Special 

        [ ]1. Credit Award

        [ ]2. Extra Ball

        [ ]3. Point Awards

*******************
***Configuration***
*******************

	
---------------------------
II. MODERN RULES
---------------------------
[ ] TODO

This ruleset is activated by keeping left flipper button when pressing start for the first player (mode is active for all players)

Unlimited balls played by each player for a duration of 2 min 30 per ball per player.
Timer starts on ball served and at the end of the timer, coils are turned off
9 missions to complete. They are off by default and represented by the lights in frontbox used for bonus lottery.
On ball serve, you choose the mission, once it's validated, it remains lit.
You need to complete all missions.
Each completed mission give you +30 sec on the Game timer.

***Ball serve*** :

    Flipper buttons navigate between each mission. 
    The mission is displayed via frontbox light (bonus lights 10 to 90)
    Mission start on first switch activated.
    Mission is lost after 3 ball drain and considered as completed (stays lit in frontbox)

***Missions*** :
* 10 - Bumper mania :
        you need to do 10 shot on each bumper to complete the mission
        When 10 shots are made on one bumper, this bumper is turned off
        Each bumper shot = 100
        Mission completed = 5000 and drain

* 20 - Cards by order :
        You need to shoot 10, then Jasper, then Queen, King and finally Ace, in the correct order.
        Other shoots are doing nothing
        Each card shot = 500
        Mission completed = 5000 and drain

* 30 - Reversed flippers :
        Left button activates Right flippers, and vice-versa
        You need to do all Card targets shots
        Each card shot = 100
        Mission completed = 5000 and drain

* 40 - Upside down :
        Left button activates Upper flippers
        Right button activates Lower flippers
        You need to do all Card targets shots
        Each card shot = 100
        Mission completed = 5000 and drain

* 50 - No Hold :
        You need to do all rollover (1-9)
        Flippers do not hold
        Each rollover shot = 100
        Mission completed = 5000 and drain

* 60 - Lanes :
        You need to do all lanes (yep, even outlanes)
        Each lane shot on the first time = 500
        Mission completed = 5000 and drain

* 70 -  Shooting range :
        Shoot the lit shot among targetrs and rollover. Complete once 10 shots are made
        Each card shot = 100
        Mission completed = 5000 and drain

* 80 - Tic Tac Toe :
        Shoot Rollover to lit a line of 3. 
        Rollin on a rollover switches between On and OFF
        Each rollover shot = 100
        Mission completed = 5000 and drain

* 90 - Slingshot contest :
        You need to activate 40 times slingshots
        Each slingshot shot = 100
        Mission completed = 5000 and drain


Once all missions are completed, you reach the Wizard mode

**WIZARD MODE !!**
	    Brings frenzy mode during 30 sec
	    All switches worth 10x
	    Chimes go crazy (TBD)
Still to be considered..

[OLD IDEAS]
**BALL SERVE**

On ball serve, the 10 bonus lights are pulsating from 1 to 10 (Value written on playfield = 1000 to 10000)

[ ] TODO

***Skill shots*** :
* Simple skill shot:

        One random light is blinking among Top lane left, Top lane right, Top rollover, one of the 3 bumpers
        Value is 0.5 * the value of the bonus light when the shot is made => up to 5000 Pts
[ ] TODO

* Hidden skill shot 1:

        Press right flipper button for 1 sec to discard skill shot lights, then shoot top right lane then directly "advance bonus" target
        Value is 1 * the value of the bonus light when the shot is made => up to 10000 Pts

[ ] TODO

* Hidden skill shot 2:

        Press left flipper button for 1 sec to discard skill shot lights, then shoot top left lane then directly "SPECIAL" lane switch
        Value is 1 * the value of the bonus light when the shot is made => up to 10000 Pts

[ ] TODO
