# XPerl Compact

**XPerl Compact** is a standalone, Sirus-focused edition of X-Perl UnitFrames for World of Warcraft 3.3.5a.

- **Version:** 1.0.0
- **Maintainer / compact edition author:** Ulcore@
- **Target client:** Sirus, Interface 30300
- **License:** GNU GPL v3

## Features

- Compact unit frames for player, target, pet, party and raid.
- Health, mana, buffs, debuffs, cast bars and related frame information.
- Raid tools and configurable unit-frame behavior.
- Sirus-specific compatibility and compact-layout changes.

## Installation

1. Close the game.
2. Extract all `XPerlCompact*` folders from the release archive into `World of Warcraft Sirus/Interface/AddOns/`.
3. Enable the required modules in the AddOns list.
4. Open settings with `/xperl`.

Do not install XPerl Compact alongside another X-Perl installation or another X-Perl fork. The code retains internal XPerl global identifiers and saved-variable names for continuity, so running both at once can cause conflicts. Back up your `WTF` folder before replacing an existing installation.

## Modules

- `XPerlCompact` — core
- `XPerlCompact_Options` — configuration interface
- `XPerlCompact_Player`, `XPerlCompact_Target`, `XPerlCompact_Party`, `XPerlCompact_RaidFrames` — unit and raid frames
- Other `XPerlCompact_*` folders — pets, cast bars, raid tools and optional features

## Sirus Launcher updates

Each module TOC contains an `X-Sirus-Update` URL pointing to its corresponding folder in this repository. The launcher should track each module from GitHub.

## Credits and license

Based on **X-Perl UnitFrames** by **Zek (Nymbia)**, with subsequent community-maintained code and the Sirus adaptation lineage associated with **Sesqiwake**. **Ulcore@** maintains this separate Compact edition and its Sirus-specific changes.

This project is distributed under **GNU General Public License v3**. The complete license is included as `XPerlCompact/LICENSE.txt`. Original copyright and license notices are retained in the source files.
