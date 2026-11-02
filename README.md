# Slaw Skyblock - Completion Tracker

Status of completing **Slaw Skyblock**, Cole's Hypixel Skyblock-style server plugin, with much less grind for 1-2 hour/day players.

**Visual tracker:** open [index.html](index.html) (or the GitHub Pages site, if enabled). Data lives in [status.json](status.json); README and page are generated from the same data.

Statuses: Done / Built, not deployed / In progress / Waiting on Cole / Brainstorming / To do

## Part 1: Dark-content cleanup

| Status | Item | Issue |
|---|---|---|
| Done | Demonic reforge removed (already gone) |  |
| Built, not deployed | Summoning Eye → Ender Catalyst, internal ID renamed with legacy ID alias |  |
| Built, not deployed | RNGesus / "God" references removed (RNGesus Meter → RNG Meter) |  |
| Built, not deployed | Necron armor/blade/heads → Titan's |  |
| Built, not deployed | Removed completely: Mega Luck Charm, Warlord (ex Necromancer) items, Radiant (ex Necrotic) reforge, Lucky Dice, Rag Doll, Herbalist/Bat masks, Lifeline Bow, Harvester (ex Reaper) items | [#1](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/1) |
| Built, not deployed | Remove Cloth Scrap, Sweeper's Broomstick, Bat Fang, Warlord slayer title, and everything Sadan | [#25](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/25) |
| Built, not deployed | Mob renames: Zealot → Ender Sentinel, Voidling Fanatic/Extremist → Brute/Warden, Voidgloom Seraph → Colossus, Ghoul → Crypt Zombie | [#2](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/2) |
| Waiting on Cole | Revenant line name: Rotting Brute / Iron Brute / Bulwark Zombie, or keep | [#26](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/26) |
| Waiting on Cole | Borderline dark-content list review | [#3](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/3) |

## Part 2: Less grind

| Status | Item | Issue |
|---|---|---|
| Done | 64 per enchanted recipe everywhere (219 recipes + compactor verified) |  |
| Built, not deployed | Bug: Enchanted Lava Bucket recipe outputs Enchanted Iron | [#4](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/4) |
| Built, not deployed | Bug: Enchanted Charcoal made from Coal | [#5](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/5) |
| Built, not deployed | Bug: Enchanted Fermented Spider Eye / Eye of Ender single-ingredient recipes | [#6](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/6) |
| Built, not deployed | Bug: Super Compactor Enchanted Bone Block typo | [#7](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/7) |
| Built, not deployed | Bug: compactor uses 64 blocks (576 diamonds) per enchanted item | [#8](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/8) |
| Built, not deployed | Bug: 48 enchanted items have no crafting recipe | [#9](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/9) |
| Built, not deployed | Bug: pet XP table skips levels 28/53/78 | [#11](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/11) |
| Built, not deployed | Enchanted Ender Pearl now 16 (recipe + compactor) | [#10](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/10) |
| To do | Rescale enchanted NPC sell prices (~1.1x ingredients) | [#12](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/12) |
| To do | Skill XP curve L16+: halve L16-30, ~1/3 for L31-60, keep 1.25x | [#13](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/13) |
| To do | Halve outlier collections (Redstone, Gemstone, Mithril, Hard Stone, Iron, Ghast Tear) | [#14](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/14) |
| To do | Halve slayer start costs | [#15](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/15) |
| To do | Minions ~30% faster | [#16](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/16) |
| To do | Review reforge costs, NPC buy prices, Kat | [#17](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/17) |

## Part 3: Economy & systems design

| Status | Item | Issue |
|---|---|---|
| In progress | Economy (approved): Hypixel base-item prices, weekly snapshot, buy/sell spread, no-arbitrage checker | [#27](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/27) |
| Brainstorming | Fairy Souls redesign (174 souls now, 5 per Tia exchange) | [#28](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/28) |

## Part 4: Wiki

| Status | Item | Issue |
|---|---|---|
| To do | Hypixel-style wiki on GitHub Pages | [#18](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/18) |
| To do | Crafting-grid recipe pages | [#19](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/19) |
| To do | Guides and drop odds | [#20](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/20) |
| To do | Player profile viewer from periodic Mongo stats export (no direct DB access) | [#21](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/21) |
| To do | Next-step recommendations | [#22](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/22) |

## Part 5: Deployment

| Status | Item | Issue |
|---|---|---|
| To do | Back up live jar, Cole's OK + restart window, deploy to hub + island | [#23](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/23) |

## Security

| Status | Item | Issue |
|---|---|---|
| Waiting on Cole | Security housekeeping (private notes) | [#24](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/24) |
