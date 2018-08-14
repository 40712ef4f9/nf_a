#####
# Installation
#####

Put this mm_** & nf_** folders into \extensions folder of X:Rebirth, so in the end it looks like

X Rebirth\extensions\mm_uspprod
X Rebirth\extensions\nf_base
X Rebirth\extensions\nf_hol
X Rebirth\extensions\nf_to
X Rebirth\extensions\nf_ls
X Rebirth\extensions\nf_hegi
X Rebirth\extensions\nf_prosdv

Each folder is a mod(-part) and will activated if conditions match

It is absolutely necessary to start a new game after install this mod!
In case you have performance issues at new-game-start by reason of your CPU, try to start with difficult setting "normal" or lower (at "hard" and higher the number of ships is always significantly higher) and change the setting afterwards.

#####
# 3rd Mod support
#####

Will NOT WORK together with CWIR-mod or an CWIR-based-Savegame!!

For some Mods are compatibility patch-mods includet (but that Mods not directly required, also official DLC are optional too)
- LostSectors [1.30] :: https://forum.egosoft.com/viewtopic.php?t=392085
- Herschels Gift [1.10] :: https://forum.egosoft.com/viewtopic.php?t=395381
|-- Vacana Ltd. Ships [1.1] :: https://forum.egosoft.com/viewtopic.php?t=399151
|-- Paladin Destroyer [1.01] :: https://forum.egosoft.com/viewtopic.php?t=399009
- Extinguished Hope [1.01] :: https://forum.egosoft.com/viewtopic.php?t=398765
- Prosper Devries [2.10] :: https://steamcommunity.com/sharedfiles/filedetails/?id=795568195

Mods to change the combat AI can work, but can have unwanted side effects

Boarding modification Mods may not work without adaptation to NF

#####
# Credits
#####

This mod based on CWIR from BlackRain&Rubini so special thanks to all people who make this possible

 BlackRain 
 Rubini 
 Pref 
 Marvin Martian 
 YorrickVander 
 DaveDee 
 w.evans 
 copperzinc 
 BerserkKnight 
 jth 
 Airstrike Ivanov 
 Unitrader 
 Reaperx
 alexalsp

#####
# Random Information
#####

* Mod-Config-Setting
the Config is available InGame by calling a Police-Chief (5-8 as far available, most sectors have one you need to find the zone he is waiting)

* NPC-Station-Building and Invasions can be disabled and this is default at the Plot-Start, so do better not enable by ourself, this will be started at the right time

* EWS (EarlyWarningSystem)
EWS have levels: 
- level 1: will always warning if at least one enemy military xl or l ship is present in a zone which player have a capitalship or station
- level 2: 50% chance for 1 enemy capship present and 100% chance when 2 or more enemy capship are present (the default now) 
- level 3: 33% for 1 enemy capship present, 50% when 2 enemy capship are present, 100% chance when 3 or more are present 
- level 4: 25% for 1 enemy capship present, 50% for 2 enemy capship present, 75% when 3 enemy capship is present and 100% when 4 or more enemy capship is present 
- EWS_Level cutoff: the minimum number of enemy ships to trigger EWS. So, you can have EWS to level 4 but a cutoff of 1. It will works with chances as above but only for 2 or more enemy units and so on. Can be set by config.

* Jumpdrive
you can configure jumpbehavior of ships in the mod-setting, there are the levels
- vanilla
- through gates (ship will jump instead of fly, based on skills)
- advanced (if skills are high enough the ship can jump directly into targetzone)

* it is also the cheat-option to disable fuelcell consume of playerowned ships available, so no extra mod is required (feel free to use, or not)

* beside of classic scan and smalltalk all stations, you can build now a Commercial Center with the HoL-CV. The Manager will then searching for new Stations and Tradeupdates (default a CC will work with the whole Galaxy, this can be limited to the System it is build)

* by dropping a NavBeakon you can call a delivery service for Weaponplattforms and more

* Manage your Shipyard
- call SY over property list -> Shipyard settings 
  "Set up a trade ware" (Manage additinal tradeware at price and amounts, but do NOT use this UI to add/change at production wares)
  "Do NPC Buildorders" yes (accept orders from other factions) / friends (or better) / members / no (do not accept new Orders, queue orders will processd anyway - Queue can controlled buy call a shipdealer -> special constructions top left option at mouseover) 
  "Shoppingbreak" (time Manager won't start new construction at orders, can used to fill ressources)

* Building own Shipyard and Unique Stations
	A CV can build also not predefined Stations, here you must first get the Station blueprint!
** get blueprint: You need a Architect (and in case a Engineer) at the Skunk, then you have a Conversation option (with the Architect) if you are docked at a Station (the Blueprint you want)
	-- at relation mid Member (≥28) you get it for free
	-- at relation Friend, you need to pay a fee
	-- at relation neutral, you can steal the blueprint: but here you need a good skilled Architect and Engineer to have only a small chance, if your heist will discovered the station come hostile for up to 24h
** preset blueprint at a CV: 
	-- you need the CV (or more then one if you like) in your Squad at the local Zone. 
	-- Talk to your Skunk-Architect and select the Station you want to build (if you have blueprints), then set the Blueprint to all or only a selected CV.
	-- Use CV like always, with selection of a buildspot, or order to build at a Zone by talking to Architect - Then you can use the regular Stations the CV do build (top-left), or you can Order the "Special Blueprint" if preset (option left and right of menu) left-option build only the base Station as always, right will directly continue after each step and build the station up to max
	
* Diplomatics
  - you can adjust your reputation, or trade zones/stations by call a NPC-Station-DefenceOfficer and use Diplomatics
  - this is also available at Mercenary-Plunder-Ships at call them, based on your Firepower you can offer Money, or force them to not do anything stupid - this will effect the behavior (from called ship) ~12-24h