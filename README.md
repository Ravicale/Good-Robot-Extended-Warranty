# Good-Robot-Extended-Warranty
An overhaul mod for the indie roguelite indie shooter, Good Robot.

## Installation:
Drag and drop all files into 'Good Robot\core\data', replace vanilla files as prompted.

## Features:
1. A comprehensive rebalance of the base game covering: weapons, upgrades, level spawns, and enemies.
2. Reworked bosses that are meatier and more challenging.
3. Enemies now have a chance to drop blue health pickups upon death, providing a non-money related means of repair.
4. ~~13~~ 14 new weapons to shoot bad robots with!
5. A variety of other QOL changes.

## New Weapons: 
- ### Tier 1:
  - Micro-Grenade Cannon: Fires small, short range grenades in an arc.
  - Plasma Cutter: A melee weapon, will probably get you killed. Possibly the most powerful weapon in the game if you don't die.
  - Magnet Gun: A comically small railgun. Fires a single piercing projectile with incredible accuracy.
- ### Tier 2:
  - Beatmaster: Shoot long range soundwaves to a fixed rhythm every 220 ms.
  - Spark Arc: Spew out a short range stream of uncontrolled electricity that arcs between groups of enemies. Very weak vs bosses.
  - Holdout Laser: Shoot small, sorta accurate lasers to supplement your main damage. Benefits greatly from ROF increases.
  - Duster: Protect both your crops and yourself from missiles and bad robots through the power of high speeds.
- ### Tier 3:
  - Khronos: Fires a volley of nasty projectiles that eventually move.
  - Nanobot Swarm: Summon a small army of nanobots that home in and consume bad robots... every once in a blue moon.
  - Plasma Caster: Rapidly fires a slow moving, boss shredding volley of plasma balls.
  - Singularity Generator: Rescued from the cutting room floor, fires a menacing blob of brightly colored death.
- ### Tier 4:
  - Stormcloud: Bouncing, homing, multitudinous projectiles... That have mediocre range and move slowly. 
  - Grenade MG: Ever wondered what it would be like if your entire screen was explosions, this is kinda like that.
  - Flame Volley: It's like a shotgun, but less shotgunny.

## Q/A:
Q: Why did I not see a store/upgrade machine at the end of X zone?
> 'Big rooms' (marked by doors with squares connected by lines) do not have stores or upgrade machines at the end of them. This is to balance their far higher cash payout; making them more risky for their reward.

Q: Why did a health pickup kill me/knock off my hat?
> Heath pickups are actually very small, static robots that rely on attacks to heal you and kill themselves. As a result, they will knock off your hat (or potentially kill you if you have less than 6 hp). Sorry, there isn't really any other way around it ):

Q: Why is easy mode the same as hard mode?
> I'm planning to make larger changes for an easy version of the mod, stay tuned!

Q: Why are enemy projectiles less colorful?
> Enemy projectiles are one of three unified colors signifying basic info. Purple means that it's a bog standard attack that will deal damage. Orange means that it's spam that will only marginally chip away at your health. Yellow means that it's an attack that can be shot down.

Q: Why is the vision upgrade so pricey?
> The cost table for that upgrade is bugged (the game reads it from the shield cost table, I personally wish I could make it use the movement speed cost table). Devs pls fix.

Q: Are achievements disabled with this mod?
> Yes.

## Changelog:
- ### Version 1.1:
  - The previously unused Singularity Generator is now included in droplists. The weapon was left in an incomplete form in vanilla and was cleaned up in the initial release of the mod... but I forgot to add it to loot.ini and the vendors. The Singularity Generator is a tier 3 secondary that fires a piercing ball of projectiles that deals 500 damage in total after a moderate charge-up period. Think of it as a trickier, projectile based Heavy Laser.
  - Made the radial danmaku style spam attack on the second stage of the final boss fire more readable circular projectiles.
  - The SpamShooterMissiles2 enemies on level 5 drop weapons of the proper tier.
  - The level 4 miniboss now fires its bouncing projectiles every 450ms (from 300ms). It simply had the potential to deal too much damage too quickly for where it is in the game.
  - Tier 3 and Tier 4 chests now drop more cash for their rare drops. Chest levels are intended to provide a *chance* at huge earnings, but their payout scaled poorly throughout the game.
  - Trap Chests after tier 1 now have slightly more challenging spawn lists. As it stood previously, their spawn lists weren't at all threatening for their placement in the game.
  - MineLayer1s now use the 'orbit' aicore instead of the 'hitnrun' aicore. This means that they will no longer spend most of their time suicide rushing right into you.
  - Starting shields reduced to 800 and increased shield upgrade to +150 per level (from +125 per level). The increase in base health was done to prevent the player from ever being one-shot, and bring health scaling more in-line with other upgrades. However, the previous base shields made the early game slightly too easy and made glass cannon builds too attractive. This reduction should help nudge things in a more varied direction.
  - The Rate of Fire upgrade scaling was adjusted to fall off less in the late game. To compensate, the cost has been increased in line with other upgrades.
  - Made a number of changes to slightly boost the effectiveness of the Khronos in most situations. It's a very difficult weapon to use, but previously it just didn't justify the hassle.
  - Buffed the Cluster Launcher refirerate to 36 (from 40) so it is less cripplingly terrible against bosses (albiet, still weak against them).
  - Nerfed Plasma Caster refirerate to 9 (from 8). The weapon was intended to be strong against bosses with the secondary benefit of being effective vs missiles at the cost of poor range and projectile speed, but it did its job slightly too well.
  - Nerfed Bunker Buster and Inferno Cannon by increasing their cooldowns by 250ms. Their DPS was out of line for their strengths when compared to their peers.
  - Increased Warhead speed by 16% (to 0.07 from 0.06), damage by 20% (to 360x2 from 300x2), and reduced cooldown by 700ms. It was nearly impossible to use in open spaces, which are especially common on the final level. And the damage simply wasn't enough to warrant its deficiencies.
  - Moved the Ricochet missile from Tier 3 to Tier 4 (with some damage buffs). The tier 3 secondary list was getting too large, and including a more 'standard' missile type weapon in addition to the Warhead should round out the limited selection of tier 4 secondaries.
  - Nerfed the damage of weapons that offered extreme benefits from focusing almost entirely on damage upgrades: Dual Gatling Beam (30 from 32), Riot Shotgun (26 from 27), Flame Volley (82 from 90), Blunderbuss (35 from 40).