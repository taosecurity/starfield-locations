# Starfield Locations

This page lists every place in Starfield and its official add-ons that you can jump to with the console's `coc` command. It was read from the game's own data files (game version 1.16.244.0).

**View it here:** https://taosecurity.github.io/starfield-locations/

## Example

1. Open the page and type `lodge` in the search box.
2. The row for **The Lodge** says it is in New Atlantis, on Jemison, in the Alpha Centauri system. Its Editor ID is `CityNewAtlantisLodgeInt`.
3. Click **Copy** to copy `coc CityNewAtlantisLodgeInt`.
4. Save your game. Then press ~ (PC only), paste the command and press Enter.

The game loads you inside the Lodge, Constellation's headquarters in New Atlantis.

## Using the console

On PC, press the **~** key (the key under Esc) to open the console, type or paste the command, and press Enter. Xbox and PlayStation have no console. Using the console turns off achievements for that save unless you use a mod that keeps them on.

## What's on the page

- The page lists 1,118 places. Each one has a readable name, the larger place it belongs to (for example Coe Plaza in Akila City), its planet or moon, its star system, and the `coc` command with a Copy button.
- It covers the base game (with the Free Lanes update), Shattered Space, Terran Armada, Watchtower and Trackers Alliance, with buttons to show or hide each add-on.
- Places are grouped by star system, then planet, then the larger place. The page also has Popular places, a "Space only" list (planets whose only coc target is in orbit) and "No fixed planet" (procedural places).
- You can search across names, places, planets, systems and Editor IDs.

What's new: see the top of the [live page](https://taosecurity.github.io/starfield-locations/).

## Words used here

- **Console:** the PC command line inside the game, opened with ~.
- **Plugin:** a mod's data file (`.esm`, `.esp` or `.esl`). It adds or changes records in the game. Each add-on is a plugin too.
- **Record:** one thing in a plugin, such as a weapon, a quest, a location or a setting.
- **Editor ID:** a record's readable name, such as `CityNewAtlantisLodgeInt`, used by the Creation Kit and xEdit. The `coc` command takes a place's Editor ID.
- **Form ID:** a record's number, such as `0002B560`. The first two digits depend on the load order.
- **Cell:** one area of the game world, such as a building's inside or a patch of a city. `coc` stands for "center on cell".

## How it was made

- The places were read from the game's own data files, game version 1.16.244.0.
- Many outdoor town areas have no name in the game. Their names are built from the Editor ID and marked "name from ID".
- The page shows only Editor IDs, Form IDs and English names. The commands were not tested in the game for this list. Save before using `coc`, because jumping into quest places early can break quests.
- The list is regenerated after game updates.

## Found a mistake?

Open an issue: https://github.com/taosecurity/starfield-locations/issues

## Credits and license

Richard Bejtlich of [Richard Presents Starfield Essentials](https://www.youtube.com/@RichardBejtlich) made this page. More Starfield tools and references are on the [Richard Presents Development Hub](https://taosecurity.github.io/).

This is an unofficial list, not made or endorsed by Bethesda. Starfield is a trademark of ZeniMax Media.

The page is a single self-contained `index.html` with no external dependencies. Its code (layout and search) is under the MIT license; see [LICENSE](LICENSE).
