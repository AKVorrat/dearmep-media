<!--
SPDX-FileCopyrightText: © 2024 Tim Weber

SPDX-License-Identifier: CC-BY-4.0
-->

# DearMEP Media Files

This repository contains some example media files for use with [DearMEP](https://github.com/AKVorrat/dearmep).
They reside in this separate repo in order to keep the main one at a reasonable size.


## Contents

### Voice Menu Audio

The [`ivr` subdirectory](ivr) ([interactive voice response](https://en.wikipedia.org/wiki/Interactive_voice_response)) contains audio files to be played in the voice menu.
See the [IVR documentation](https://github.com/AKVorrat/dearmep/blob/main/doc/ivr.md) for more details on how the menu works.

These files have been used in our [Chat Control campaign](https://dearmep.eu/showcase/chatcontrol/).
While many of them are very generic, some (especially the talking points in `argument_*.wav` as well as `arguments_campaign_intro.*.wav` and `campaign_greeting.*.wav`) are campaign-specific or mention the campaign by name and thus would need to be replaced for other topics.


## License

The contents of this repository are licensed under the terms of the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license (`CC BY`).

The individual files are tagged accordingly.

The repository conforms to the [REUSE Specification, version 3.3](https://reuse.software/spec-3.3/).
You can use [the `reuse` tool](https://github.com/fsfe/reuse-tool) to interpret the machine-readable licensing information.
