# Custom Bingo Board
Custom Bingo Board (CBB) is a bingo board that can generate seeded, randomized bingo boards based on a goal list.

## Grouping
Goals in a goal list fed to CBB can be put into groups. Goals that share the same group can be filtered to not show up more than once on the board (Blackout mode) or more than once per row/column/tl-br/bl-tr (Rows/Columns mode). 

The option to randomize all goals regardless of grouping is also available. 

Big thanks to Numberplay and dotzo for the advice during the development of CBB.

### Example
*Exerpt from TLoZ: OoT Randomizer Goal List*
```
DODONGOSCAVERN|Defeat all Lizalfos in Dodongo's Cavern
BOW|FORESTTEMPLE|Defeat Amy (Green Poe)
JABUJABUSBELLY|BOOMERANG|Defeat Barinade
JABUJABUSBELLY|Defeat Big Octo
SHADOWTEMPLE|Defeat Bongo-Bongo
FIRETEMPLE|HAMMER|HOOKSHOT|Defeat both Flare Dancers
WATERTEMPLE|Defeat Dark Link
DODONGOSCAVERN|Defeat King Dodongo
BOW|FORESTTEMPLE|Defeat Meg (purple Poe)
WATERTEMPLE|HOOKSHOT|Defeat Morpha
IRONKNUCKLE|Defeat Nabooru-Knuckle
FORESTTEMPLE|BOW|HOOKSHOT|Defeat Phantom Ganon
DEKUTREE|Defeat Queen Gohma
```
Note: Groups are only pipe `|` delimited. Groups may have spaces and other special characters. 
## Common Goal Lists
* [TLoZ: OoT Randomizer (glitchless)](https://pastebin.com/raw/18Mtdwng)
* ... more to come ?

## Changelog
 * `v1.0.0` release  
 * `v1.0.1` small fix for chrome browsers not displaying tables correctly
 * `v1.0.2` add distribution groups and saving saves square state (red/green/black)
 * `v1.0.3` distribution selectors saved when saving and random seed clears board
 * `v1.0.4` update button and text input positions / fix localStorage boolean bug
 * `v1.0.5` check tlbr/bltr in row/column mode

## Online Version
http://bingo.sav.estate/
