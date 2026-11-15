<p align="center"><img src="images/wick-thumb-beasts.png" alt="Wick's Beasts and Things"></p>
# Wick's Beasts and Things

<!-- wick:badges:start -->
[![Downloads](https://img.shields.io/curseforge/dt/1708162?style=flat-square&labelColor=171124&label=downloads&color=4FC778)](https://www.curseforge.com/wow/addons/wicks-beasts-and-things)
![Forever](https://img.shields.io/badge/client-Forever-383058?style=flat-square&labelColor=171124)
[![License](https://img.shields.io/badge/license-MIT%20%2B%20trademark-383058?style=flat-square&labelColor=171124)](LICENSE)
[![Discord](https://img.shields.io/badge/discord-join-4FC778?style=flat-square&labelColor=171124)](https://discord.gg/GWGTMhYBZY)
<!-- wick:badges:end -->

> Hunter loadout kit for World of Warcraft: Forever. Pet care with one-key feeding, ammo watch, talents, pre-pull checklist, racials.

Part of the **[Wick suite](https://github.com/Wicks-mods/WickSuite)**: precision addons built around a single fel-green-on-deep-purple aesthetic. Built on [WickCore](https://github.com/Wicks-mods/WickCore).

## What it is

A hunter's setup is a pet and a quiver. This kit keeps both in view and
handles the chore that every hunter repeats a hundred times: feeding.

- **Pet card.** Name, family, level, happiness with damage bonus and loyalty
  direction, loyalty rank, free training points, and what the pet eats.
- **Feed key.** One keybind that casts Feed Pet and uses the best food in
  your bags that this pet will actually eat, judged by the client's own
  diet check and the level rule. Pin a specific food with a slash command
  when you would rather burn the cheap stuff.
- **Ammo watch.** What is in the ammo slot, how many shots are equipped and
  in reserve, and whether it matches the weapon. Red below your threshold
  or when arrows meet a gun.
- **Talents.** Export the active build as a Blizzard import string, import a
  string as a new loadout, save builds to an account-wide library, apply one
  with a click.
- **Pre-pull checklist.** Aspect up, pet out, pet fed, ammo stocked, Trueshot
  Aura once you have it. Rows go quiet the moment combat starts.
- **Racials.** Your race's actives as cast buttons with cooldown display.

## Install

Requires **[WickCore](https://github.com/Wicks-mods/WickCore)**. Extract both
folders into the Forever client's `Interface\AddOns\`.

## Usage

Bind **Feed pet** and **Toggle pet and ammo panel** under Key Bindings,
AddOns, Wick's Beasts and Things.

| Command | Effect |
|---|---|
| `/wbt` | Pet and ammo panel |
| `/wbt kit` | Talents, checklist, racials |
| `/wbt options` | Options page |
| `/wbt ammo <count>` | Warn below this many shots |
| `/wbt food [item link]` | Pin a food for the feed key |
| `/wbt food clear` | Back to the best food in bags |
| `/wbt status` | Diagnostics |

`/wbeasts` is an alias.

## Compatibility

World of Warcraft: Forever, 1.60.x, Interface 16001. Requires WickCore.

## More from Wick

<!-- wick:suite-table:start -->
| Addon | GitHub | CurseForge |
|---|---|---|
| **WickCore** | [repo](https://github.com/Wicks-mods/WickCore) | [CurseForge](https://www.curseforge.com/wow/addons/wickcore) |
| **Wick's Comforts** | [repo](https://github.com/Wicks-mods/WicksComforts) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-comforts) |
| **Wick's Beasts and Things** | [repo](https://github.com/Wicks-mods/WicksBeastsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-beasts-and-things) |
| **Wick's Stances and Things** | [repo](https://github.com/Wicks-mods/WicksStancesAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-stances-and-things) |
| **Wick's Seals and Things** | [repo](https://github.com/Wicks-mods/WicksSealsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-seals-and-things) |
| **Wick's Conjures and Things** | [repo](https://github.com/Wicks-mods/WicksConjuresAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-conjures-and-things) |
| **Wick's Poisons and Things** | [repo](https://github.com/Wicks-mods/WicksPoisonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-poisons-and-things) |
| **Wick's Demons and Things** | [repo](https://github.com/Wicks-mods/WicksDemonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-demons-and-things) |
| **Wick's Bags** | [repo](https://github.com/Wicks-mods/WicksBags) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-bags) |
| **Wick's Trade Hall** | [repo](https://github.com/Wicks-mods/WicksTradeHall) | [CurseForge](https://www.curseforge.com/wow/addons/trade-hall) |
| **Wick's Gear** | [repo](https://github.com/Wicks-mods/WicksGear) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-gear) |
| **Wick's UI** | [repo](https://github.com/Wicks-mods/WicksUIForever) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-ui) |
| **Wick's Reminders** | [repo](https://github.com/Wicks-mods/WicksReminders) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-reminders) |
| **Wick's Map** | [repo](https://github.com/Wicks-mods/WicksMap) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-map) |

**Community:** [Discord](https://discord.gg/GWGTMhYBZY)
<!-- wick:suite-table:end -->

## License

MIT for code (see [LICENSE](LICENSE)). Brand chrome and the "Wick's" wordmark are trademarked, see [TRADEMARK.md](https://github.com/Wicks-mods/WickSuite/blob/main/TRADEMARK.md). Racial data from [talentsforever.com](https://talentsforever.com) (CC BY 4.0) via WickCore.
