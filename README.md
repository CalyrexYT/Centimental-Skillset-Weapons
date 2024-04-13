# Skillset Centimental Season 2: Weapons

This mod is specifically created for the Centimental SMP. It adds weapons (that have abilities) to Minecraft 1.20.4 (will be updated to 1.20.5, then 1.21)


## Usage

Download the jar file named: skillset-centimental-[version number]-mc1.20.4.jar
Add it to the fabric mods folder in minecraft
Run fabric 1.20.4 v0.15.6

##  Weapons added:

1. Prison of Souls:
- Mid-endgame item
- Every kill increases the sword's sharpness level by 1, the highest level is 50
- The higher the sharpness level, the harder it is to upgrade it's sharpness (to upgrade from lvl 1-2 is 90% chance, lvl 2-3 is 86% chance, etc.)
- Base damage 7

2. Mjolnir:
- Endgame item
- Obtained from killing the ender dragon, drops once
- Cannot be destroyed (i.e cactus, lava, void, fire)
- When thrown, explodes on impact; If it hits a mob, strikes lightning as well
- Base damage 10

3. Chorus of the Void (WIP):
- Endgame item
- 10% chance to create a black hole on hit: black hole sucks in entities in a 15 blocks radius (all entities are forced to follow trajectory towards black hole)
- if in contact with the black hole, deals wither 5 level damage
- Can create up to one pairs of portals, allow for fast travel, portals disappear when player enters and exits (WIP)
- Base damage 9

## Change Log
v0.1.0
-  Added Prison of Souls

v0.1.1
-  Nerfed Prison of souls sharpness increment, max sharp 30
-  Buffed Prison of souls increment chance
-  Buffed Prison of souls damage to 7 (prev 6)

v0.2.0
- Added Mjolnir

v0.2.1
- Nerfed Mjolnir explosion size to 4 (charged creeper) previous 7 (bedrock wither/larger than crystal)
- Fixed Prison of souls increment
- Fixed Mjolnir void teleportation issue, now teleports when its at bedrock level or lower

v0.2.2
- Buffed Prison of souls sharpness increment, max sharp 50
- Nerfed Mjolnir melee damage to 10

v0.3.0
- Added Chorus of the Void

v0.3.1
- Added black hole feature to chorus of the void
- Added Riptide feature to mjolnir (crouch and throw to riptide, riptide 5)

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
