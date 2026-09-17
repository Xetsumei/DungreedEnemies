# DungreedEnemies 1.2.6

[Download the latest release ZIP](https://github.com/Xetsumei/DungreedEnemies/releases/latest)

[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

An AddOn that brings 90 normal Dungreed enemies and its bosses into Sephiria’s top-down combat. Six mini-bosses now also appear naturally on their assigned floors.

## Features

- Each normal spawn slot has a 50:50 choice between a vanilla enemy and a Dungreed enemy for that floor. This does not guarantee an exact half in each room.
- Mini-bosses share equal selection chances with the floor’s vanilla mini-boss encounter and use its stats and rewards. Floors 1, 2, 3 and 5 have a 1/2 chance each for vanilla or DE; floor 4 has a 1/3 chance each for vanilla, Raiona or Livna. These are the defaults before EM bans or randomization.

| Floor | Added mini-boss |
| --- | --- |
| 1 | Asterios, Prison King's General |
| 2 | Squiata, Yielding Soldier |
| 3 | Impulsive Jumper, Enhanced Robot |
| 4 | Raiona, Coloso Boca · Livna, Witch Sword |
| 5 | Naglfar, Loyal Vassal of the Ark |

- Hard mode’s **Blood Festival** heals each DE enemy at most **once every 2 seconds**. The first eligible hit heals immediately; rapid hits and hits on multiple players share that attacker's cooldown. Native healing amounts and boss/multiplayer scaling are retained. Vanilla enemies and other healing effects are unaffected.
- With EM installed, you can ban normal enemies and mini-bosses from its lists. EM, QoL and ModMaker are optional.
- Names follow the game language: Korean, English, Japanese or Simplified Chinese.
- Slime Maker, Arsha, Ericha, Erta Alle and Devana do not yet appear naturally.

## Installation

Close the game, create `Sephiria/AddOns/DungreedEnemies`, and extract the ZIP contents into it. `metadata.json`, `DungreedEnemies.dll`, `DungreedEnemies.pak` and `Libs` must sit directly inside that folder. For a manual update, overwrite the files in the same location.

## Automatic updates

When you enter the game, the mod checks for a new version. In the lobby, choose Update now, Remind me later, or Skip this update. Update now downloads the release and restarts the game. Automatic prompts and restarts are postponed during a run.

Use `/de update` to check manually, `/de update off` to turn off automatic checks, and `/de update on` to turn them back on. A manual check also shows a version you skipped.

Downloads are verified before installation. Your settings carry over. If a release changes Libs, download the ZIP and install it with the game closed.

Older versions without this feature need one manual ZIP installation first.

[Update history](patchlog_en.md)

After entering the game, once your character and chat display are ready, a single `[DungreedEnemies] Up to date.` notice or a new-update notice appears. Update prompts wait for other mods’ prompts to close. Disabled checks and skipped versions do not show an automatic update prompt.
