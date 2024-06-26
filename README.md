# Pokémon PureRGB-FakeMime

To see the full list of features, bugfixes, and everything else, see [**FEATURES.md**](FEATURES.md)

If you want info on the game while playing it (learnsets, for example), see [**The Wiki**](https://github.com/ViWalls/pureRGB-FakeMime/wiki)

This is an enhancement of Pokemon Red/Blue/Green. The goal is to enhance the original games for excellent replayability without bringing in mechanics, moves, sprites, visuals, type matchups, or pokemon that were introduced in later games. 
- It makes the bulk of the 151 original pokemon all more obtainable and usable in the early game, with better movesets and more balanced stats. 
- Many moves in the game were rebalanced or modified. When I say "rebalanced", I mean "the useless things were made more useful!" 
- There are more bug, poison, and ghost type moves available. The focus is on getting a useful set of moves available for every single pokemon in the game. 
- Front sprites were updated to be just about the best set of sprites from Red/Green/Blue/Spaceworld 1997 overall.
- All 151 pokemon are obtainable in all versions of this hack. 
- [Many small quality-of-life tweaks and bugfixes](https://github.com/ViWalls/pureRGB-FakeMime/blob/master/FEATURES.md#quality-of-life-enhancements) were made. 
- Game bugs that can be used to your own advantage (like the leech seed/toxic bug, the hyper beam no recharge on faint bug, etc.) are unchanged, because they are quirks of the battle engine that you can use as your own tool. 
- Mew is under the truck as expected!
- Missingno and the item duplication glitch are intact - but won't corrupt your save anymore!
- An entirely new mode for the pokedex called the MOVEDEX was added. It shows data about moves you have seen in detail. You unlock the MOVEDEX in viridian city.
- There are multiple secret areas to be found after becoming CHAMP. Bills Garden, Team Rocket / Mewtwo lore, and more...
- [Many options to enhance the game visually and mechanically were added.](https://github.com/ViWalls/pureRGB-FakeMime/blob/master/FEATURES.md#new-options-in-the-options-menu) **(You must turn them on via the options in-game!)** Including:
  - Switchable color palettes (Choose between original colors, Super Gameboy Colors, or Pokemon Yellow Colors in-game whenever you like! Works on GBC and Super Gameboy. Yes, this romhack has GBC support!)
  - Optional Spaceworld 1997 Back Sprites
  - Optional enhanced menu sprites/overworld icons
  - Optional enhanced music (Add in cut content music like Giovanni's theme) 
  - Optional stereo panned audio (Similar to the Earphone1 option in Pokemon Yellow)
  - Optional alternate color palette pokemon based on region (catch differently colored pokemon depending on where they appear in Kanto)
  - Option to turn off the bicycle song (plays in cycling road still)
  - Tweak the type matchups to be exactly like gen 1, gen 2, or a cross between them if you like directly in-game.
  - Optional in-battle experience bar
  - Option to give trainers some Stat EXP to their pokemon based on level. Makes the game a little bit harder.
- If you're playing on GBC and have the palettes set to SGB or GBC mode, move animations will have colors! Surf will be blue, ember will be red, etc.
- There are a couple entirely new things added into the game to facilitate quality of life fixes. Including:
  - An NPC who can permanently remove CUT trees.
  - An NPC who can revive fossils for you in SAFFRON CITY so you can get fossil pokemon a bit earlier.
  - An NPC who will give you LAPRAS a bit earlier in the game.

## Fork changes

- The front sprite of Mr. Mime was replaced by Fake Beta Mr. Mime that was [debunked by Dr. Lava](https://twitter.com/DrLavaYT/status/1284462794532773888?s=20), sprite included with [other accurate recreations of real Beta Pokémon of Gen I by unknown artist](https://github.com/ViWalls/pureRGB-FakeMime/blob/master/screenshots/RedBlueBetaPokemon.png).
- The back sprite of Mr. Mime was replaced by a custom one provided by **metalflygon08** for SW97. I only changed the light reflection in the back because the original felt flat for my tastes in a sphere head. The one in Gen I style it's made by me but based in the SW97/Gen II previously provided to match the same design.
- Why I do this small change? Because I have despised Mr. Mime original design all my life. It never was a solid playable Pokémon neither due to its ridiculous HP and Defense values. On PureRGB it was overhauled and improved with an amazing Psychic/Ghost dual type making it an unique choice for your team, but his appearance was still annoying me. Plus I always wanted to first contact Github with a simple task and navigate through his interface aside from build something considering the time I spend following projects here. You should play original PureRGB unless you hate Mr. Mime as much as I do.

![fakemime](/screenshots/FakemimetitleRed.png?raw=true) ![fakemime](/screenshots/fakemime.png?raw=true) ![fakemimedex](/screenshots/fakemimedex.png?raw=true) ![fakemimeb](/screenshots/fakemimebgen1.png?raw=true) ![fakemimeb](/screenshots/fakemimeb.png?raw=true)

Pictured: Title Screen (Red OG) Front Sprite (SGB), Pokedex Data (SGB), Back Sprite Gen I (SGB), Back Sprite SW97 (Red OG).

If someone is interested or want to use these sprites for his own projects it's fine. You have the version of **metalflygon08** who provided the back sprite but made some changes from original fake design OR the one I made using the previous one as base, where I reverted those minor changes loyal to original art and extended the footprint one pixel long, matching my perception of its foot anatomy.

![FakeMimebymetalflygon08](/screenshots/FakeMimebymetalflygon08.png?raw=true) ![FakeMimebyViWalls](/screenshots/FakeMimebyViWalls.png?raw=true) ![FakeMimeSprite](/gfx/pokemon/front/mr.mime.png?raw=true) ![FakeMimeBackSpriteGenI](/gfx/pokemon/back/mr.mimeb.png?raw=true) ![FakeMimeBackSpriteSW97](/gfx/pokemon/back_sw/mr.mimeb.png?raw=true)

- The front sprites of Squirtle evolution line were upgraded to Squirtle Squad.
- Also the back sprites of Squirtle evolution line were upgraded in the process to match the front ones. Squirtle (Gen I), Wartortle (Gen I) & Blastoise (SW97) are provided as a contribution by **[Blazer](https://www.deviantart.com/steppoblazer)**.

![SSquadFrontRB](/gfx/pokemon/front/squirtle.png?raw=true) ![SSquadFrontRG](/gfx/pokemon/front_alt/squirtle.png?raw=true) ![WSquadFrontRB](/gfx/pokemon/front/wartortle.png?raw=true) ![BSquadFrontRB](/gfx/pokemon/front/blastoise.png?raw=true) ![BSquadFrontRG](/gfx/pokemon/front_alt/blastoise.png?raw=true) ![SSquadBackSpriteGenI](/gfx/pokemon/back/squirtleb.png?raw=true) ![WSquadBackSpriteGenI](/gfx/pokemon/back/wartortleb.png?raw=true) ![BSquadBackSpriteGenI](/gfx/pokemon/back/blastoiseb.png?raw=true) ![SSquadBackSpriteSW97](/gfx/pokemon/back_sw/squirtleb.png?raw=true) ![WSquadBackSpriteSW97](/gfx/pokemon/back_sw/wartortleb.png?raw=true) ![BSquadBackSpriteSW97](/gfx/pokemon/back_sw/blastoiseb.png?raw=true)

- Changed entire Title screen Pokémon list. Now each game will have Mr. Mime (FakeMime) first, one starter evolution line depending on which game you're playing (Bulbasaur evolution line for Green, Charmander evolution line for Red and Squirtle evolution line for Blue). Then a list of different Pokémon I really like to play distributed per game to make each rom Title screen more unique. The pokeball animation will play if Mr. Mime or one of the three starters sprites scrolls.
- Some sprites were changed to suit my taste: Gastly uses RG sprite, Gengar default sprite uses RG one and the alternative SW97, Golbat default sprite uses RB one and the alternative SW97, Exeggcute alternative sprite uses RG one & Exeggutor default sprite uses RG one and the alternative SW97. The front sprites options pages were updated to follow the new format and avoid confusion, so it's pretty clear.
- Grimer Base Special was raised to 50 and Muk Base Special to 95. Now Muk it's more bulky and hard to deal with, specially with Trainer EXP activated.
- All three starters final evo were revamped in addition to their main types: Now Venusaur it's Grass/Ground, Charizard Fire/Dragon and Blastoise Water/Rock to make them more unique. Also the learnsets were slightly tweaked to match the new dual typings: Venusaur learns Earthquake by level up, Charizard gets Dragon Rage (level up/TM) and Egg Bomb (level up), finally Blastoise gets Explosion by level up plus Rock Slide using a TM. Those moves were revamped in PureRGB so they will get STAB thanks to new types.
- Krabby/Kingler are now Water/Normal types. Crabhammer it's their signature, exclusive move and Ground moves prior to PureRGB were replaced by Normal ones following vanilla criteria. Is still weak to Electric moves but it has now different strategies and powerful Normal STAB moves.
- Added a splash of Physical Special Split for Crabhammer (now a Physical Water move) and Night Shade (now a Special Ghost type move already revamped in PureRGB, even more useful on this fork).
- Gastly/Haunter/Gengar are now Ghost/Normal types. The only poison move he can learn aside from Toxic, Filthy Slam, was replaced with Wrap to gain trapping strategies. Is still fragile but not as it was due to original Poison dual type.
- Poliwrath was revamped: HP, Attack and Defense base values were increased to 100. Also front and back sprite (Gen I) were replaced using **Helix Chamber** reconstructions based on Nyosuka Poliwrath Prototype from Green Beta (thanks to **catstorm26** & **RacieBeep**). SW97 back sprite was made by me using Poliwrath's one as base with some tweaks and modifications to maintain accuracy and loyalty to design.

![NyosukaFrontRB](/gfx/pokemon/front/poliwrath.png?raw=true) ![NyosukaBackSpriteGenI](/gfx/pokemon/back/poliwrathb.png?raw=true) ![NyosukaBackSpriteSW97](/gfx/pokemon/back_sw/poliwrathb.png?raw=true)

- Gyarados Bite was replaced with Fury Attack, added Roost and Whirlwind to its learnset. Added Roost and Fly to TM/HM learnset.
- Arbok was revamped to dual Poison/Dragon type: Attack base increased to 105 and Special base to 95, plus Egg Bomb was added to its learnset. It can learn Dragon Rage using a TM.
- Armored Mewtwo base stats reverted to vanilla Mewtwo base stats. Now both are identical and it's only a visual sprite change but still worth the effort.
- Victreebel was reverted to vanilla Grass/Poison type. Egg Bomb was removed from Bellsprout/Weepinbell/Victreebel learnset and replaced with Sludge, also Dragon Rage was removed from Victreebel TM learnset.
- Horsea/Seadra now learn Egg Bomb at level 54.
- Pinsir now uses Tricules sprites from SW97. In addition, the alternate sprite you can toggle in options was updated using **SourApple** desing for Gold & Silver 97: Reforged, with some modifications in shading to match the style of the original front in demo (the original front is marked as SW in sprite options, the alternative as DX). The Gen I style back sprite was made by **Albatross** and used in Kanto Expansion Pak. The reason behind this choice it's I wanted to have Tricules here, but Pinsir was revamped in PureRGB with an interesting dual typing and it was difficult to find the perfect spot for it. Also I wanted to maintain the original 151 number and improve the existing ones instead of going crazy.
- Lickitung base stats were improved: 110 HP, 85 Attack, 95 Defense, 50 Speed and 80 Special (based on Lickilicky from Kanto Expansion Pak). Because I'm not a huge fan of Lickitung design I replaced all the sprites with Lickilicky ones: the front sprite and Gen I style back sprite were made by **Albatross** (both used in Kanto Expansion Pak). Finally the Gen II style back sprite for SW97 mode was made by **Blue Emerald**.

## Credits

**Vortyne** - Obvious reasons. No master, no fork.

**Jojobear13** - Tons of code snippets and help via the shinpokered romhack codebase, direct support regarding the pokemon yellow gbc enhancements porting.

**Danny-E 33** - Larger back sprites code snippets, EXP Bar code snippets, various support regarding game audio and questions about rgbasm/gbz80 answered.

**Mechanicalpen** - enhanced menu icons code.

**LJSTAR** - Most of the work creating the type icons used in the movedex.

**Mord** - Most of the work creating LT.Surge and Erika overworld sprites.

**pret discord** and **pret** in general for their original disassembly work on Red / Blue.

**Smogon University** - the cornerstone of competitive pkmn.

**ZoomTen** - share some knowledge about coding plus helping to prevent ROM bank overflow amongst other things like resolve conflicts to track PureRGB updates. Also priceless support that made FakeMime a thing.

**metalflygon08** - providing SW97 back sprite of fake Mr. Mime.

**pokeglitch** - creating pret_manager and making easier build to test changes.

**Blazer** - providing back sprites for Squirtle Squad and encourage me to finish Squirtle Squad.

**Plague von Karma** & **Martha, the Programmer Girl** - inspiration, a shitload of things related to Kanto Expansion Pak development and valuable feedback to enhance certain pkmn.

**Lilyhollow** - some reference following Violet Version Showdown mod. Even if I'm not following the same criteria and changes, I think it's a great point to start cultivating ideas for revamping trashy pkmn.

**Albatross** - Gen I style Tricules back sprite and Lickilicky front sprite.

**SourApple** - Gen II style Tricules alternative front sprite.

**Blue Emerald** - Gen II style Lickilicky back sprite.
