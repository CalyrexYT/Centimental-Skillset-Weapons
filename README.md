# Skillset Centimental Season 2: Weapons

This mod is specifically created for the Centimental SMP. It adds weapons (that have abilities) to Minecraft 1.20.5 (releasing next week) (then 1.20.6, 1.21)


## Usage

Download the jar file named: skillset-centimental-[version number]-mc1.20.4.jar
Add it to the fabric mods folder in minecraft
Run fabric 1.20.4 v0.15.6

MORE EXCITING UPDATES COMING SOON!

## Known Bugs
- Explosion from mjolnir sometimes create ghost blocks
- Model of thrown mjolnir is buggy
- Prison of souls removes all enchantments when upgraded
- Black hole spawns when hit is registered, meaning you can spam hit the weapon to spawn black holes really quickly
- Portals are supposed to disppear when a player enters, but it only removes the one you entered, not the one you exited
- Portals are not limited to two sets

##  Weapons added:

1. Prison of Souls:
- Mid-endgame item
- Every kill increases the sword's sharpness level by 1, the highest level is 50
- The higher the sharpness level, the harder it is to upgrade it's sharpness (to upgrade from lvl 1-2 is 90% chance, lvl 2-3 is 86% chance, etc.)
- Base damage 8

2. Mjolnir:
- Endgame item
- Obtained from killing the ender dragon, drops once
- Cannot be destroyed (i.e cactus, lava, void, fire)
- When thrown, explodes on impact; If it hits a mob, strikes lightning as well
- Base damage 11

3. Chorus of the Void (WIP):
- Endgame item
- 10% chance to create a black hole on hit: black hole sucks in entities in a 15 blocks radius (all entities are forced to follow trajectory towards black hole)
- if in contact with the black hole, deals wither 5 level damage
- Can create up to one pairs of portals, allow for fast travel, portals disappear when player enters and exits (WIP)
- Base damage 14

## Change Log
<strong>v0.1.0</strong>
-  Added Prison of Souls

v0.1.1
-  Nerfed Prison of souls sharpness increment, max sharp 30
-  Buffed Prison of souls increment chance
-  Buffed Prison of souls damage to 7 (prev 6)

<strong>v0.2.0</strong>
- Added Mjolnir

v0.2.1
- Nerfed Mjolnir explosion size to 4 (charged creeper) previous 7 (bedrock wither/larger than crystal)
- Fixed Prison of souls increment
- Fixed Mjolnir void teleportation issue, now teleports when its at bedrock level or lower

v0.2.2
- Buffed Prison of souls sharpness increment, max sharp 50
- Nerfed Mjolnir melee damage to 10

<strong>v0.3.0</strong>
- Added Chorus of the Void

v0.3.1
- Added black hole feature to chorus of the void

v0.3.2
- Added black hole velocity feature (no longer tp entities)
- Apply wither damage to non-player entities, wither IV
- Black hole no longer affects non-living entities

v0.3.3
- Nerfed black hole velocity feature to be 60% slower
- Black hole affects non-living entities again
- All entities now follow path towards black hole no matter their initial velocity
- Fixed mjolnir despawn issue when inside black hole
- Fixed wither effect range to be 3 blocks around the black hole (prev 15)

v0.3.4
- Black hole now adds the attraction velocity instead of overwriting it (entities maintain their initial velocty, such as arrows, pearls, now still have their momentum)
- Buffed wither damage to be wither V
- Fixed issue where if the mjolnir hits an entity, the explosion is still lvl 7 (fixed to 4)

v0.3.5
- Black hole now attracts non-living entities the strongest, non-player mobs second strongest, and players the weakest
- Fixed Prison of souls unlimited sharpness stacking, maxed at lvl 50

v0.3.6
- Black hole now applies multiple negative effects when the 10 sec duration ends
- Rebalanced the amount of velocity the black hole applies onto living entities and players
- Fixed Prison of souls sharpness stacking (prev reaches 51)

v0.3.7
- Black hole end effects are now applied for 10 seconds instead of 10 ticks (0.5 sec)
- Buffed all weapon damages
- Fixed several instances of redundant code

v0.3.8
- Changed Mjolnir explosion type to hopefully fix ghost blocks? (not confirmed)
- Added portals for chorus of the void, summoned by holding the weapon and pressing the keybind (default R)
- Updated known bugs

v0.3.9
- Mjolnir explosing type did not fix ghost blocks, now reverted to mob explosion to increase the blast range
- Added a fun new feature for a certain weapon that is very hard to obtain!

v0.3.10
- Added new block chorus ore, no functionality yet
- Updated how prison of souls work, now there is a chance for the sharpness level to decrease too
- Uploading file to release section now
- This section is no longer maintained, check releases for details
