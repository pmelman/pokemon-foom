<p align="center">
  <img src="title%20screen.jpeg" alt="Pokémon Foom title screen" width="100%">
</p>

# Pokémon Foom

A ROM hack of Pokémon Emerald satirizing rationalism, the AI industry and Bay Area culture, set in the region of
Barria. Two rival labs race toward a Pokémon superintelligence.

**v0.1 (alpha).** Expect bugs, placeholder art and unfinished areas. Saves may not carry over to the next version.

## Download

[`pokemon-foom-0.1.bps`](pokemon-foom-0.1.bps) is a patch, not a game. It doesn't include Pokémon Emerald, and we
can't give you one. Please share the patch, never a patched ROM.

## What you need

A Pokémon Emerald (USA, Europe) ROM, as a `.gba` file:

| | |
| --- | --- |
| CRC32 | `1F1C08FB` |
| SHA-1 | `f3ae088181bf583e55daf962a92bb46f4f1d07b7` |

Other versions (Japanese, German, French...) and ROMs that are already patched won't work. The patcher checks the
ROM and stops if it's the wrong one.

## How to patch

1. Open [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) in a browser (nothing to install), or use
   [Flips](https://github.com/Alcaro/Flips/releases).
2. Choose your Emerald `.gba` as the ROM and `pokemon-foom-0.1.bps` as the patch.
3. Apply, and save the result, for example as `Pokemon Foom 0.1.gba`.

Then play it in [mGBA](https://mgba.io), or any GBA emulator that runs Pokémon Emerald.

## What's in v0.1

The first three gyms, from Talltree Town through Sandhill Town, Mount Vista and Valley City to Fogshore City, and
the routes between them. Later gyms, the Elite Four and the end of the story aren't in yet.

## About the game

- **Region:** Barria, a fictionalized Bay Area. 
- **Premise:** Vertex Labs enhances Porygon. OpenAether works on genetically engineering pokemon.
- **Characters:** figures from the Bay Area tech scene are parodied with lightly re-named stand-ins.
- **Gyms** are themed around ideas, not types.
- **Porygon** is received early and is one of your core Pokemon companions.
- **Barrail** (Barria's Caltrain) connects the towns.

## The map

Barria's Town Map, as it appears in the game (and for Fly):

<p align="center">
  <img src="Barria%20map.png" alt="Barria's Town Map" width="480" style="image-rendering: pixelated;">
</p>

## Feedback and bug reports

Please [open an issue](../../issues/new/choose). A bug report or a note on difficulty, pacing or writing are both welcome.

A good bug report has:

- the game version (`0.1`) and the emulator you used
- where it happened and what you were doing
- a **save state** (`.ss1`, `.ss2`...) from just before the problem, if you can. It's the easiest way to reproduce a bug.

## Built on

The game is built on the [pret pokeemerald](https://github.com/pret/pokeemerald) decompilation and
[pokeemerald-expansion](https://github.com/rh-hideout/pokeemerald-expansion) 1.17.0 by the ROM Hacking Hideout and
its contributors.

Pokémon sprites come with pokeemerald-expansion, including fan sprites from PokéCommunity's "DS-style Gen VII and
Beyond Pokémon Sprite Repository in 64x64" and by ezerart, Darkus_Shadow, Princess-Phoenix, shaderr31, Molfang62,
CarmaNekko, EduarPokeN, Larryturbo, TyranitarDark, Anarlaurendil, Eemeliri, Gerben BSc and lichen. See
pokeemerald-expansion's changelogs for the full history.

## Legal

Pokémon and all related names, characters and images are trademarks and copyright of Nintendo, Creatures Inc. and
GAME FREAK inc. Pokémon Foom is a free, non-commercial fan project and isn't affiliated with or endorsed by them.
Don't sell it.

Barria is satire. Characters who resemble real public figures are parodies.

Created by Paul Melman
