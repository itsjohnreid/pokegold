# Pokémon Pure Gold

This is a mod of the disassembly of Pokémon Gold and Pokémon Silver forked from pret/pokegold.

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
- Fast text speed by default
- Increase shiny odds to 1/256 (All DVs are >= 12)
- Red Gyarados has all 13 DVs (to ensure it's still shiny with new criteria).
- Lugia/Ho-Oh re-learn signature moves at level 70
- Evolution stones sold at Mahogany Mart (after Rocket's gone)
- King's Rock sold at Azalea Mart
- Metal Coat sold at Olivine Mart
- Dragon Scale sold at Blackthorn Mart
- Evolution items all cost 2100
- Ghost is Special
- Dark is Physical
- Added Move Reminder in Move Deleter's house

## Bug Fixes
- Fixed Dragon Scale not Dragon Fang boosting dragon type moves
- Party menu item renamed from MOVE -> MOVES
- Fix Rival DVs in Kanto
- Burn/Poison/Paralyze now correctly increases catch chance
- Fix Moon Ball
- Fix Love Ball
- Fix Fast Ball
- Fix catching a transformed pokemon always catching a ditto

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

Legendaries:
- Articuno Lvl 50 - Route 25 (1%)
- Zapdos Lvl 50 - Route 10 (1%)
- Moltres Lvl 50 - Route 21 (1%)
- Mewtwo Lvl 70 - Silver Cave (1%)
- Mew Lvl 50 - Route 1 (1%)
- Celebi Lvl 5 - Ilex Forest (1%)

Starters:
- Bulbasaur - Route 1 (30%)
- Charmander - Route 1 (30%)
- Squirtle - Route 1 (30%)
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
- Phanpy - Route 45, 46 (Morn 10-20%)

Johto stuff you could only find in Kanto before:
- Houndour - Route 36, 37 (Night 10%), Route 8 (Night 5%)
- Sneasel - Ice Path (Night 5%)
- Misdreavus - Sprout Tower (Night 15%)
- Slugma - Burned Tower B1F (20%)

Extra:
- Weedle - Ilex Forest (Morn/Day 30%)
- Teddiursa - Dark Cave (Morn 5%)
- Ursaring - Dark Cave Blackthorn Side ( Morn/Day 10-15%)

### Sprites changed to silver version
(Asterisk ones not actually changed yet but I want to later)
- Vulpix
- Jigglypuff
- Ponyta *
- Rapidash
- Muk *
- Cloyster *
- Goldeen *
- Scyther *
- Ditto
- Vaporeon
- Porygon *
- Omastar
- Kabutops *
- Articuno *
- Zapdos *
- Cyndaquil *
- Typhlosion *
- Xatu *
- Umbreon *
- Murkrow *
- Girafarig *
- Delibird
- Mantine
- Donphan
- Blissey
- Celebi

## Moves
- (NEW) Buzz - Bug, 70 power, 100 accuracy, 20pp, 20% to confuse
- (NEW) Shriek - Ghost, 70 power, 100 accuracy, 20pp, 30% to flinch
- (NEW) Venom Fang - Poison, 70 power, 100 accuracy, 20pp, 30% chance to poison
- Cut 70 power, 20pp
- Flash 50 power, 100 accuracy, 50% accuracy reduction, 20pp
- Mud Slap 50 power, 100 accuracy, 50% accuracy reduction, 20pp
- Waterfall 30% flinch chance
- Rock Smash 50 power
- Whirlpool 35 power, 85 accuracy
- Fire Spin 35 power, 85 accuracy
- Lick 30 power
- Vine Whip 40 power, 25pp
- Poison Sting 25 power
- Leech Life 40 power
- Mega Drain 15pp
- Giga Drain 70 power, 10pp
- Comet Punch 20 power
- Pin Missile 20 power
- Fury Swipes 20 power

## Buffs
### Butterfree
- Buzz level 45
- +15 Spatk = 95

### Beedrill
- Buzz level 45
- +15 Atk = 95

### Pidgeot
- +12 HP = 95
- +9 Speed = 100

### Nido line
- Venom Fang instead of Bite/Fury Attack

### Zubat
- Venom Fang level 58

### Golbat/Crobat
- Venom Fang level 65

### Arbok
- Venom Fang instead of Acid (and ekans)
- +25 Atk = 110
- +11 Spdef = 90

### Parasect
- +20 HP = 80
- +20 Atk = 115

### Venomoth
- +20 Spatk = 110
- +15 Spdef = 90

### Persian
- +15 Atk = 85

### Rapidash
- Flame Wheel instead of Ember (and ponyta)
- Egg move flamethrower
- +20 Spatk = 100

### Gastly line
- Shriek egg move

### Farfetch'd
- +50 Atk = 115
- +30 Speed = 90

### Dewgong
- +10 Spdef = 115
- +20 Speed = 90

### Hypno
- +15 HP = 100

### Voltorb/Electrode
- Spark at level 29

### Lickitung
- +20 HP = 110
- +15 Atk = 70
- +10 Spatk = 70

### Seaking
- +30 HP = 110
- +18 Atk = 110

### Scyther/Scizor
- Buzz at level 54

### Vaporeon
- Bubble Beam instead of Water Gun

### Jolteon
- Spark instead of Thundershock

### Flareon
- Flame Wheel instead of Ember

### Meganium
- +20 HP = 100

### Furret
- +10 Speed = 100
- +4 Atk = 80

### Noctowl
- +24 Spatk = 100
- +4 Spdef = 100
- +20 HP = 120

### Ledian
- Buzz egg move
- +30 Atk = 65
- +20 Spatk = 75
- +10 Spdef = 120

### Ariados
- Venom Fang instead of Fury Swipes (and spinarak)
- +30 Atk = 120
- +15 HP = 85
- +15 Spatk = 75

### Lanturn
- +14 Spatk = 90

### Togetic
- +25 Def = 110
- +20 Spatk = 100
- +15 Spdef = 120

### Xatu
- +20 Atk = 95
- +5 Spatk = 100
- +5 Speed = 100

### Azumarill
- +50 Atk = 100
- +20 Def = 100
- +20 Spdef = 100

### Sudowoodo
- +15 Atk = 115
- +20 HP = 90

### Jumpluff
- +25 HP = 100
- +20 Speed = 130

### Aipom
- Mega punch instead of Scratch
- +10 All stats

### Yanma
- Quick Attack level 1
- Sonicboom level 7
- Wing Attack level 19
- Buzz instead of Supersonic
- +25 Atk = 90
- +15 Spatk = 90
- +35 Speed = 130

### Quagsire
- +20 Spatk = 85

### Murkrow
- Wing Attack level 21
- +20 Atk = 105
- +9 Speed = 100

### Misdreavus
- Shriek instead of Psybeam
- Psybeam egg move
- +25 Spatk = 110
- +25 Spdef = 110
- +25 Speed = 110

### Unown
- Psychic
- Teleport
- Double Team
- 88 all stats

### Girafarig
- +10 HP = 80
- +5 Atk = 85
- +20 Spatk = 110
- +15 Speed = 100

### Forretress
- +20 Atk = 110

### Dunsparce
- Dig instead of Spite
- +80 HP = 180

### Gligar
- Mud Slap instead of Sand Attack
- +30 Atk = 105
- +20 Speed = 105

### Qwilfish
- +40 Spatk = 95
- +10 Speed = 95

### Shuckle
- +40 HP = 60

### Sneasel
- Fury Swipes level 1
- Quick attack level 9
- Icy Wind level 33
- +60 Spatk = 95

### Magcargo
- +30 HP = 80
- +30 Atk = 80

### Swinub
- Earthquake level 55

### Piloswine
- Earthquake level 66
- +20 Spatk = 80

### Corsola
- +20 Def = 105
- +30 Sptk = 95
- +20 Spdef = 105

### Delibird
- +75 HP = 120
- +65 Atk = 120

### Mantine
- +40 Atk = 80
- +20 HP = 85

### Houndour
- Venom Fang egg move

### Skarmory
- Wing Attack instead of Swift
- +20 Speed = 90

### Houndoom
- +20 Atk = 110

### Stantler
- Mean Look instead of Sand Attack
- +7 HP = 80
- +15 Atk = 110
- +3 Def = 65
- +15 Speed = 100

### Smeargle
- +15 Speed = 90

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
