Safe Zone Commander
======
This script allows the following configuration options to be enabled for your trader zones:

(To configure an option, set the option to true or false near the top of the file.)

Safe zone Godmode (Compatible with the sensors script, i will post this at the bottom in the credits)

Safe zone enter/exit messages (as well as some others)

Safe zone Anti Backpack stealing:

- Allow to loot from loot piles in safe zones
- Allow to loot from vehicles in safe zones
- Allow to loot from dead players in safe zones
- Allow looting from a vehicle if you are inside it

Disable guns from being able to shoot bullets and/or projectiles

Disable mounted guns from being able to shoot bullets and/or projectiles

Requirements 
=====
Easy = <10mins

You are expected to have some knowledge of how to pack/unpack pbo's.

Installation Steps
=====
-Download master branch of repo
-Unpack your mission PBO using your favorite pbo manager (I use PBO MANAGER personally).
-Inside your mission directory (where you extracted your pbo to), extract the folder AGN inside this folder.
-Open the missions init.sqf at the very bottom insert:
	[] execvm 'AGN\agn_SafeZoneCommander.sqf';
	
Picture/Video
====
- None

Credits
====
- AlienX original arther of Safezone Commander (http://opendayz.net/threads/epoch-safe-zone-commander-god-anti-backpack-stealing-no-shooting-no-vehicle-weapons.14877/)
- The original concept for godmode by maca (http://dayzepoch.com/forum/index.php?/topic/386-better-safezone-maybe/)
- The snippet for no shooting in trader zones (Unsure Where i found this now!)
- Safezone Sensors by MGT (http://dayzepoch.com/forum/index.php?/topic/1490-safezone-god-mode-for-all-trading-posts/?p=10283)