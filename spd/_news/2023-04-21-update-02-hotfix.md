---
layout: spd
title: Update v0.2 Hotfix
---

# Quality of Life Improvements

Among bug fixes, I've included so many changes that I've decided to write an announcement. The major gameplay change I added is allowing the tower's ability to evolve at a lower level. Before players had to upgrade to level 10, but I've noticed that it's difficult to reach it without power ups and knowing the strategy beforehand. Now you can see it at level 8! Hopefully people will notice this surprise power spike!!!

Tower Change
* Previously towers had to be level 10 to get the bonus effect. This has been reduced to level 8.

Prompt Changes
* Prompts shown throughout the game have been updated to have more clear wording. Unfortunately players who have seen those prompts will not be able to see them again (sorry!)
* The Power Up menu wording has been changed to not use the vague word "Tier". Now it will show the starting health/money, how much less each tower will cost, and how the DPS will be improved.

Bug Fixes
* Even with all the protections I added, players are still seeing a crash that I can't reproduce. I've concluded that there may be an issue related to the built-in unreal engine function, so I wrote my own function instead. Fingers crossed that this solves the problem once and for all!
* Leaderboards have been fixed. The built-in unreal system for Steam leaderboards doesn't work (we're seeing a common trend here). So I ended up rewriting it to use a different system.
* For the leaderboards, I added "OG" badges on the players who played v0.1. This is mainly to test if players will like this kind of reward system in the future.

Tutorial Update
* Tutorial enemies meshes (except for the peasant) have been changed to be standard. This will make things less confusing for new players.
