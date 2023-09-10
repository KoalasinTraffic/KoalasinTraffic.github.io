---
layout: spd
title: Update v0.8 Truly Endless
---

# Truly Endless

The last hotfix I made introduced bugs, but they should be fixed now. The new wall tower should allow you to fix your maze despite the bosses' abilities. And finally, endless mode is now almost truly endless!

For endless, your computer may experience performance issues due to having too many enemies in the game... Don't forget to use items as they deal percent damage. Also, I added a beta global leaderboard system, several bug fixes, and balanced some of the towers.

Wave generation
* Health and damage datatypes have been changed to handle values up to 1e300.
* Endless waves technically stop once the potential score you can get reaches 2 billion, but I highly doubt anyone can reach it.
* Serfs are now significantly easier at high levels. Before, their health increased faster than the main waves. Now, it's been changed to be calculated based on the main wave's health.
* Points you can make: [https://koalasintraffic.github.io/spd/scoring](https://koalasintraffic.github.io/spd/scoring)
* Money you can make: [https://koalasintraffic.github.io/spd/money](https://koalasintraffic.github.io/spd/money)

Mazing
* Push backs and sucking from the Dragon and Final Boss have been changed for mazing only. Now they will deal 10 damage to towers (same amount of damage as the Kraken). This will make mazing a lot less random than before.
* Fixed bug where the Final Boss could swap the new wall tower.

Tower updates
* Max tower level has been increased to 100.
* Wall tower sell value has been changed so it gives the full refund.
* Beam tower can no longer be displaced or swapped to prevent making the tower useless. Beam visuals have been reduced for better visibility.
* Slow tower has been significantly nerfed. Slow starts at 6% and maxes at level 8 with a 48% movement reduction.
* Stun tower bonus damage to bosses is now x3 again. Bosses are just really annoying to deal with...

Buff weapon
* Changed to heal for 10% of the tower's max health instead of just 1 HP. This allows you to heal any tower to full with a single buff (12 second duration).

Leaderboards
* A global leaderboard has been added. Basically high scores from all levels are summed together. This will be re-calculated for players with save files pre-0.8 and whenever you get a new high score.
* Although not actually tracked on the leaderboards, the maximum waves reached is now a local stat. This can be viewed before starting a level.
* A cheat detection has been added in beta mode. Please contact me if you get this error message!!!

Miscellaneous changes
* Fixed bug where the stun trap would make the level up sound.
* Fixed bug where the slow tower would spawn a cannonball.
* Boss music now only plays at level 30, 60, 90, and etc instead of at every boss wave.
* The shuffle music button is now available at any time, and is placed at a more intuitive location in the options.
* Super serfs visuals now appear at level 100. Just a cosmetic thing.

