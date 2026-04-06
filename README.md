# Fishin Time

A browser-based fishing RPG built with vanilla JS and Canvas.

## How to Play

Open `fishing-game/index.html` in a browser. No install needed.

Walk around the world and stand next to any body of water to cast your line. A minigame bar appears — keep the moving zone over the fish dot to reel it in. The harder the fish, the smaller the zone and the faster it moves.

Controls are tap/click based, fully playable on mobile.

## World & Biomes

The world is a large open map with multiple unlockable fishing spots:

| Area | Unlock Cost |
|---|---|
| Pond | Free |
| River | $200 |
| The Docks | $300 |
| Ocean | $600 |
| Frozen Lake | $900 |
| Deep Sea | $2,500 |
| Volcano Island | $5,000 |
| Midnight Zone | $8,000 |

Each biome has its own fish pool, ambience sounds, and weather interactions.

## Fish Rarities

common → uncommon → rare → epic → legendary → mythic

Mythic fish are locked behind the skill tree. Some fish only appear during specific weather events (rain, fog, aurora).

## Mutations

Caught fish can randomly roll a mutation that multiplies their sell value:

- Golden (3x), Albino (2x), Giant (2.5x), Shadow (4x), Crystal (5x)

## Rods

13 rods available in the Rod Shop, each with unique stats and a special ability:

- Stick Rod (free starter) up to the Mythic Rod ($20,000)
- Biome-specific rods: Swamp Rod, Coral Rod, Volcano Rod, Ice Rod, Abyss Rod
- Specialty rods: Speed Rod (fastest cast), Tank Rod (biggest zone)

## Bait

5 bait types sold at Bait Shops — boosts luck or catch speed per cast.

## Skill Tree

42 upgrades across 3 categories:

- Luck — rare fish chance, sell value multipliers
- Skill — zone size, cast speed, double catch chance
- Extra — EXP bonuses, weather bonuses, mutation chance, night fishing

## Weather Events

Weather changes dynamically and affects fish availability and luck bonuses. Rain unlocks storm-exclusive fish. Aurora and fog have their own rare spawns.

## Progression

Catch fish → earn EXP → level up → unlock skill points. Sell fish at the Sell Fish buildings in town or at the docks.
