# DungreedEnemies 1.1.1

[한국어](README_ko.md) · [English](README_en.md) · [日本語](README_jp.md) · [中文](README_zh.md)

An AddOn that brings 90 normal Dungreed monsters and 8 boss families into Sephiria’s top-down combat. Normal enemies appear naturally from the candidates for each floor. Devana remains excluded from natural spawns.

## 1.1.1 — 2026-09-15

- Release update history is available in the `patchlog` files.

## Features

- Each normal spawn slot has a 50:50 choice between a vanilla enemy and a Dungreed enemy for that floor. This does not guarantee an exact half in each room.
- There is no separate settings panel. With EM installed, you can ban these enemies from its lists. EM, QoL, and ModMaker are optional.
- All 107 normal enemy, boss, and supporting entity names follow the game language: Korean, English, Japanese, or Simplified Chinese.
- F8 testing tools are disabled.

## Installation

Extract the ZIP into `Sephiria/AddOns/DungreedEnemies`. Keep `metadata.json`, the DLL, and `Libs` together. Keep `DungreedEnemies.pak` alongside them.

## Automatic updates

When you enter the game, the mod checks for a new version. In the lobby, choose Update now, Remind me later, or Skip this update. Update now downloads the release and restarts the game. Automatic prompts and restarts are postponed during a run.

Use `/de update` to check manually, `/de update off` to turn off automatic checks, and `/de update on` to turn them back on. A manual check also shows a version you skipped.

Downloads are verified before installation. Your settings carry over. If a release changes Libs, download the ZIP and install it with the game closed.

Older versions without this feature need one manual ZIP installation first.

[Update history](patchlog_en.md)

After entering the game, once your character and chat display are ready, a single `[DungreedEnemies] Up to date.` notice or a new-update notice appears. Update prompts wait for other mods’ prompts to close. Disabled checks and skipped versions do not show an automatic update prompt.
