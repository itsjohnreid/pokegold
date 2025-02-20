# Pokémon Gold and Silver [![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon Gold and Pokémon Silver forked from pret/pokegold.

It builds the following ROMs:

- Pokemon - Gold Version (UE) [C][!].gbc `sha1: d8b8a3600a465308c9953dfa04f0081c05bdcb94`
- Pokemon - Silver Version (UE) [C][!].gbc `sha1: 49b163f7e57702bc939d642a18f591de55d92dae`
- mons2_gld_ps3_debug.bin `sha1: 53783c57378122805c5b4859d19e1a224f02a1ed`
- mons2_slv_ps3_debug.bin `sha1: 4c2fafebdbc7551f4cd3f348bdd17e420b93b6e7`
- DMGAAUP0.J56.patch `sha1: b8253b915ade89c784c71adfdb11cf60bc1f7b59`
- DMGAAXP0.J57.patch `sha1: a38c0dec807e8a9e3626a0ec0fdf96bfb795ef3a`

To set up the repository, see [INSTALL.md](INSTALL.md).

# Changes
## General
- Increase shiny odds to roughly 1/105 (if all DVs are greater than 11)
- Red Gyarados has slightly stronger DVs (to ensure it's still shiny with new criteria).
- Lugia/Ho-Oh re-learn signature moves at level 70
- Evolution stones sold at Cianwood Mart
- Ghost is Special
- Dark is Physical
- Fixed Dragon Scale not Dragon Fang boosting dragon type moves

## Evolutions
- Kadabra using Everstone
- Machoke using Everstone
- Haunter using Everstone
- Graveler using Everstone
- Scyther using Metal Coat
- Seadra using Dragon Scale
- Onix using Metal Coat
- Porygon using Up Grade
- Poliwhirl to Politoed using King's Rock
- Slowpoke to Slowking using King's Rock

## Pokemon Locations
Trades:
- Trade Dragonair for Larvitar (holding lucky egg)
- Kenya is now a Murkrow

Legends:
- Articuno Lvl 50 - Route 25 (1%)
- Zapdos Lvl 50 - Route 10 (1%)
- Moltres Lvl 50 - Route 21 (1%)
- Mewtwo Lvl 70 - Silver Cave (1%)
- Mew Lvl 50 - Route 1 (1%)
- Celebi Lvl 5 - Ilex Forest (1%)

Starters:
- Bulbasaur - Route 1 (30%)
- Charmander - Route 1 (30%)
- Bulbasaur - Route 1 (30%)
- Chikorita - Route 44 (30%)
- Cyndaquil - Route 44 (30%)
- Totodile - Route 44 Surf (30%)

Non-Gold exclusives:
- Omanyte - Rock Smash anywhere (10%)
- Kabuto - Rock Smash anywhere (10%)
- Vulpix - Route 36, 37 (Morn 10%), Route 7, 8 (Morn 10-20%)
- Meowth - Route 38, 39, 5, 6, 7, 8 (20-30%)
- Ledyba - Route 30, 31, 37, 2 (Morn 30-40%)
- Delibird - Ice Path (20%)
- Skarmory - Route 45 (5%)
- Phanpy - Route 45, 46 (Morn 10%)

Johto stuff you could only find in Kanto before:
- Houndour - Route 36, 37 (Night 10%), Route 8 (Night 5%)
- Sneasel - Ice Path (Night 5%)
- Misdreavus - Sprout Tower (Night 15%)
- Slugma - Burned Tower B1F (20%)

Extra:
- Weedle - Ilex Forest (Morn/Day 30%)

## Moves
- Cut 70 power
- Vine Whip 25 pp
- Poison Sting 25 power
- Fire Spin 35 power, 85 accuracy
- Whirlpool 35 power, 85 accuracy
- Waterfall 20% flinch chance
- Rock Smash 45 power
- Flash 30 power, 100 accuracy

## TMs
These Kanto city marts sell TMs:

### Viridian
- 1 Dynamic Punch
- 15 Hyper Beam
- 24 Dragon Breath
- 38 Fire Blast
- 39 Swift

### Pewter
- 4 Rollout
- 23 Iron tail
- 26 Earthquake
- 28 Dig
- 47 Steel Wing

### Cerulean
- 14 Blizzard
- 16 Icy Wind

### Lavender
- 30 Shadowball
- 50 Nightmare

### Vermilion
- 7 Zap Cannon
- 25 Thunder

### Celadon
- 19 Giga Drain
- 22 Solar Beam
- 49 Fury Cutter

### Fuchsia
- 6 Toxic
- 36 Sludge Bomb

### Saffron
- 29 Psychic
- 42 Dream Eater
- 44 Rest
- 46 Thief
