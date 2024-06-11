# Sonic the Fighters: Remix
StF:Remix is a hack of the original arcade version of Sonic the Fighters, including some new features to help give the game a new spin.

## Features
* **Honey, Dr. Eggman (mech and mechless forms) and Metal Sonic have all been added to the CSS**: They're in invisible slots to the right of Knuckles, and can be picked normally.
* **Restored random mode**: Hold P1 or P2 punch while pressing start on the title screen, to play random mode, with the unused CSS remixed music restored. You'll be given a randomized set of characters to fight against in story mode, without repeats, including the following extra characters: Honey, mechless Eggman, RoboEgg, Metal Sonic and Super Sonic.
* **Remix alt mode**: Hold P1 or P2 kick while pressing start on the title screen, to enable remix mode. Currently has 3 costumes: Super Sonic, Amy with Honey's attire and alternate color Honey (for Player 1). All three characters with costumes will fight their normal color counterpart instead of a grayscale clone in mirror matches.
* **No ketchup damage mode**: Hold P1 or P2 barrier/block while pressing start on the title screen, to enable no ketchup damage mode. Catchup damage (colloquially known as "ketchup" damage) makes characters take more damage depending on some factors like health lead and such, and this mode allows disabling that.
* **Unused music restored**: Random mode makes use of the unused CSS music remix, Sunset Town will play on Dynamite Plant if any player is Honey, and Hurry Up! plays in Death Egg's Hangar.
* **Other changes**: Some miscellaneous bugfixes and unused content restored from the original game, such as the unused ice blocks in Aurora Icefield.

## Known bugs
* The Super Sonic costume's head will revert to normal Sonic when in his losing animation. I was unable to fix this.
* If Eggman (mechless 1 or mech) or Roboegg are in Aurora Icefield, most of the background elements will flicker.
## Not bugs
* The Super Sonic costume reverts back to normal Sonic while he's squished. There's no model for a squished Super Sonic, so I reverted the head as well so it at least makes sense.

## TODO
Add the rest of this document! :p (explaining install, more known issues, and probably more)

Note, this disasm hasn't been tested with the official Intel assembler, and I'm only using the included `binutils` in the `GNU/` directory of this repository.
As a tip, to compile binutils for i960 support, use `./configure --target=i960-elf32`
