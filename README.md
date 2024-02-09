# Sonic Time Twisted PS3 port
This is a port of the fan game Sonic Time Twisted for the PS3, the original source code can be found [here](https://github.com/overbound/SonicTimeTwisted).

This port is more of a "Proof of concept" rather than a full port. Code-wise, it's the same as the PS4 version.
This was compiled using the recently released [GayMaker-PS3](https://github.com/LiEnby/GayMaker-PS3) tool.

## Notes
This was compiled using the "Playstation" profile, "Fast Collision" enabled, but without YYC option.

## How does this run?
The PS3 runner is not has optimized as the PS4/Vita runner, so, here are the issues:
1. There's this blue-ish/green-ish color over **a lot** of objects. Player sprite included.
2. Performance FPS-wise is slow. The game *is* playable, but expect 1 second in-game to sometimes be 4 seconds in real life...
3. Saving works, async, **but** the PS3 takes a lot of time saving. To the point that, if you break 4 life monitors in a row, the game will hang **badly** (it won't crash, but it will take some time to recover).
4. The game may hang sometimes, but it will not crash. If you're playing and the game seems to have frozen, give it some time, and it will come back to "normal".
**Still**, there **is** a possibility that the game may crash and you'll have to turn off the PS3 on the button.
5. Play with the expectation of other miscellaneous issues that I may have forgotten to add here.

## Credits
Original game by [Overbound Game Studio](https://overboundstudio.com).

## Licensing

*All copyrights and registered trademarks of 'Sonic the Hedgehog', all associated characters, art, names, terms and music belong to SEGA®, and are not subject to any licenses associated with this project. The contributors to this software are in no way affiliated with SEGA® or Sonic Team®, nor is any intent made to gain financially from or infringe upon said copyrights or registered trademarks.*

*Music from the soundtrack "Dueling Ages" by Hinchy et al. is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. If, for any reason, a copy of said license is not present within this repository, you can view and/or download it by visiting: http://creativecommons.org/licenses/by-nc-sa/4.0/*
