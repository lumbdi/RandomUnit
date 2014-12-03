RandomUnit
==========

Custom game inside Dota 2. Spawn as a random unit kill as many as possible. My first coding project.

Description: Each player is given a random unit. If your unit kills another unit gain a point. If your unit dies spawn a new random unit. Winner is decided by most kills.
Additional information:

Chance of spawning a level 2 unit is higher than spawning a level 1/3 unit.
Map is small and simple. May have cliffs, trees and teleporters
Map is always lit.
Teleporters teleports you from one end to another
Runes may spawn which gives you haste, regeneration or one powerful attack (first right click from you does 9999 damage).
Trees are scattered far from each other (relevant for Tiny)
Paths are generally narrow

Game Mode (priority low):
Option of having bots with standard AI (standard aggro)
Free for all or teams. If uneven gain AI
First player to load in is given a unit to set mode
If 10 second passes and no mode is picked other players are also given a unit
After additional 20 seconds mode with most units is set
If draw random mode

Types of units that may spawn: (all units have 0 armor)
Level 1:
Small Satyr: ranged, 20 damage, can use purge (instantly kills summons)
Spiderling: high movement speed , 5 damage
Level 2:
Shadow Shaman: Can cast shackle, immobilize and deal damage.
Wolf: Decent movement speed, good damage, low health.
Gyrocopter: Rocket barrage deals good damage, movement speed a bit below average, low health
Lycan: normal movement speed, good damage, normal health
Sniper: Very slow, low damage, can attack from far range
Level 3:
Tiny: Slow movement speed, slow attack speed, high turn rate. Can one-hit all Level 1 units, most level 2 units. Kills Level 3 units in a few hits, can eat tree to gain cleave for 3 hits, large collision size (trapping units possible)
Broodmother: has passive that places a buff on enemy unit. If enemy unit die under buff spawn a spiderling.
Priority low: For now only implement Sniper.
