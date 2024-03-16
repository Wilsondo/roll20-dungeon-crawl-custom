# Foundry Quick Quest
The original sheet was created by the talented Giffyglyph, and can be found at [Giffyglyph's Darker Dungeons](https://github.com/giffyglyph/giffyglyphs-darker-dungeons). This character sheet has been modified to support a homebrew version of Dungeons and Dragons 4e with elements from Torchbearer.

## Differences Between This Sheet and Giffyglyph's

* The character sheet is designed to work with PC's only, NPC's use simple character tokens and macros.
* The game is run using the Dungeons and Dragons 4e game engine, not 5e.
* Wounds, survival conditions, and stress remain, but instead of exhaustion, you lose maximum healing surges.
* The features page now includes space for a goal, belief, creed, flaws and instinct, these have impact on how you play your character mechanically.
* Notes has been folded into features, and spells have been removed because of how 4e handles powers.
* Powers are found on the core page, clicking them gives you a link to the power in the 4e encylopedia. To use your power, you must click on your token and use a token macro. This will also update the checkmark on the core page to tell you if you still have that power available.
* As all powers are used through macros, prior setup on level up is required, and is generally done by the DM.

![Roll20 Character](./img/example-character.jpg)

## Getting Started

Roll20 requires a pro subscription to use custome character sheets, be sure to have one if you want to try this sheet out. 

To use this character sheet in your Roll20 D&D 4e game, you must download darker-dungeons.html, darker-dungeons.css and translations.json files from releases.

Then go to Roll20 and make a new game. When the game asks for what character sheet you want to use, select custom and upload the 3 files.

## Code Contributions

This project contains source code and build scripts to generate both development and live sheet code. If you'd like to try out some code changes and contributions—or customise the sheet for your own bespoke game—read the following:

### Requirements

1. Node.js (https://nodejs.org/en/).
2. gulp-cli (https://gulpjs.com/docs/en/getting-started/quick-start/)

### Instructions

1. Run "npm install" to install all the required node_modules.
2. Run "gulp" to build the dev/live sheets from source and automatically watch for any file changes.
3. To test locally: open _dist/dev/darker-dungeons.html_.
4. To upload to Roll20: copy _dist/live/darker-dungeon.css_ and _dist/live/darker-dungeon.html_ to Roll20.

## Licensing

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
