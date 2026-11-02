# Slaw Skyblock - Completion Tracker

Status of completing **Slaw Skyblock**, Cole's Hypixel Skyblock-style server plugin (SlawSkyblock), with much less grind for 1-2 hour/day players.

Statuses: Done / In progress / Built, not deployed / Waiting on Cole / To do. Source: AUDIT-2026-11-01.md (Grok Bot audit of SlawSkyblock source).

## Part 1: Dark-content cleanup

| Status | Item | Issue |
|---|---|---|
| Done | Demonic reforge removed (already gone) |  |
| Built, not deployed | Summoning Eye → Ender Catalyst, internal ID renamed with legacy ID alias so existing items keep working |  |
| Built, not deployed | RNGesus / "God" references removed (e.g. RNGesus Meter → RNG Meter) |  |
| Built, not deployed | Necron armor/blade/heads → Titan's |  |
| Built, not deployed | Remove completely: Mega Luck Charm (ex Arenjey God), Warlord (ex Necromancer) items, Radiant (ex Necrotic) reforge, Lucky Dice (ex Sinful Dice), Rag Doll (ex Voodoo Doll), Herbalist/Bat masks (ex Witch masks), Lifeline Bow (ex Soulstealer Bow), Harvester (ex Reaper) items | [#1](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/1) |
| Waiting on Cole | Mob/boss display renames: Zealot → Ender Sentinel, Voidgloom Seraph → Voidgloom Colossus, Ghoul/Golden Ghoul → Crypt/Golden Zombie, Voidling Fanatic/Extremist → Brute/Warden, Revenant line (display only; internal keys kept for bestiary/XP) | [#2](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/2) |
| Waiting on Cole | Borderline list review (vanilla undead, Spirit/Soul/Ghost, Death/Shadow/Dark wording, Blood items, dungeon boss names, skulls, internal class IDs) | [#3](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/3) |

## Part 2: Less grind

| Status | Item | Issue |
|---|---|---|
| Done | 64 per enchanted recipe everywhere (all 219 recipes + compactor table verified) |  |
| To do | Bug: Enchanted Lava Bucket recipe outputs Enchanted Iron (uncraftable) | [#4](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/4) |
| To do | Bug: Enchanted Charcoal made from regular Coal | [#5](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/5) |
| To do | Bug: Enchanted Fermented Spider Eye and Enchanted Eye of Ender take only 1 ingredient | [#6](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/6) |
| To do | Bug: Super Compactor never makes Enchanted Bone Block (ENCAHNTED_BONE typo) | [#7](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/7) |
| To do | Bug: compactor eats 64 blocks (576 diamonds) per Enchanted Diamond etc. | [#8](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/8) |
| To do | 48 enchanted items have no crafting recipe | [#9](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/9) |
| To do | Enchanted Ender Pearl uses 64 (Hypixel 20) and sells at a loss | [#10](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/10) |
| To do | Bug: pet XP table typos skip levels 28/53/78 | [#11](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/11) |
| To do | Sell prices still assume 160 per item → lower enchanted prices to ~1.1x ingredients | [#12](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/12) |
| To do | Skill XP curve L16+: halve L16-30, ~1/3 for L31-60, keep 1.25x multiplier | [#13](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/13) |
| To do | Collections outliers: Redstone, Gemstone, Mithril, Hard Stone, Iron, Ghast Tear | [#14](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/14) |
| To do | Slayer start costs: halve (1k/3.75k/10k/25k/50k) | [#15](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/15) |
| To do | Minions ~30% faster (or cheaper fuel) | [#16](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/16) |
| To do | Review reforge costs + NPC buy prices (+ Kat) | [#17](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/17) |

## Part 3: Wiki

| Status | Item | Issue |
|---|---|---|
| To do | Hypixel-style wiki on GitHub Pages | [#18](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/18) |
| To do | Crafting-grid recipe views generated from plugin code | [#19](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/19) |
| To do | How-to guides and drop odds pages | [#20](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/20) |
| To do | Player profile viewer from periodic Mongo stats export (no direct DB access) | [#21](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/21) |
| To do | Next-step recommendations for players | [#22](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/22) |

## Part 4: Deployment

| Status | Item | Issue |
|---|---|---|
| To do | Back up live jar, get Cole's OK + Server Admin restart window, deploy to hub + island | [#23](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/23) |

## Security

| Status | Item | Issue |
|---|---|---|
| Waiting on Cole | Rotate the LuckPerms database password (currently stored in plain text in a config) | [#24](https://github.com/ColeMcClintock/slaw-skyblock-tracker/issues/24) |
