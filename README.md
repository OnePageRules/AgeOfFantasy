![CI](https://github.com/sprutton1/GrimdarkFutureBattlescribe/workflows/CI/badge.svg?branch=master)

<!-- TOC -->
- [Introduction](#introduction) 
- [How do I use these files?](#how-do-i-use-these-files)
   - [Instructions](#instructions)
- [How can I help?](#how-can-i-help)
   - [Adding an army](#adding-an-army)
      - [Guidelines](#guidelines)
      - [What's Done](#whats-done)
   - [Reporting an issue](#reporting-an-issue)
- [Credits](#credits)
<!-- /TOC -->

# Introduction

Welcome to the Battlescribe repo for [OnePageRules'](https://onepagerules.com/)
[Age of Fantasy](https://onepagerules.com/portfolio/age-of-fantasy/). This is
a set of files to use with the [Battlescribe](https://battlescribe.net/) app to
build army lists.

You can always reach out to me on
[Discord](https://discordapp.com/channels/610199287346888743/610199287346888746)
or the [OPR Forum](http://forum.onepagerules.com/) if you need something.

# How do I use these files?

In order to use these files, you must manually add the index to Battlescribe and
then refresh the data.

The index is hosted at:

https://age-of-fantasy.s3.amazonaws.com/index.bsi

## Instructions

[Instructions for Desktop](./desktop.md)

[Instructions for Mobile](./mobile.md)

# How can I help?

## Adding an army

Open a Github issue on this page with which army you would like to see added and
assign yourself to it. We can track progress on those issues.

Then, pick an army and create a datafile for it! I suggest using the Dwarves army as an example. Once you are done, open a Pull Request and I will
review the changes before shipping them up to be indexed.

Also, if you make progress on a list, make sure you update the "What's Done"
table!

### Guidelines

1. The "Publication" entry should contain the name of the list you're
   implementing **including** the version (so we know what versions are
   current).

2. You should never add anything to the game system file (.gst) that's not in
   the main ruleset (except weapons).

3. Weapons found in multiple lists should be added to the game system file.
   Lists should use the entries from the game system file instead of entries in
   the army file itself in this case.

4. When in doubt on how to format something, feel free to ask!

### What's Done

| Army | Version | Progress | Author |
|---|---|---|---|
|Game System|v2.10|Done|Darguth|
|Beastmen|v2.4|Done|cartag|
|Chivalrous Kingdoms|v2.5|Done|Darguth|
|Dark Elves|v2.6|Done|Darguth|
|Deap-Sea Elves|v2.5|Done|Darguth|
|Duchies of Vinci|v2.3|Started|strongbif|
|Dwarves|v2.9|Done|Darguth|
|Eternal Wardens|v2.7|Done|PerramUnderhill|
|Ghostly Undead|v2.5|Done|Darguth|
|Giant Tribes|v2.0|Done|Darguth|
|Goblins|v2.10|Done|Darguth|
|Halflings|v2.3|Done|Darguth|
|Havoc Dwarves|v2.2|Done|Darguth|
|Havoc Warriors|Main v2.9 - Disciples v2.10|Done|cartag (Main), Darguth (Disciples)|
|High Elves|v2.7|Done|Darguth|
|Humans|v2.9|Done|strongbif|
|Kingdom of Angels|v2.3|Done|Perram|
|Mummified Undead|v2.8|Done|Darguth|
|Ogres|v2.4|Done|Darguth|
|Orcs|v2.7|Done|Darguth|
|Ossified Undead|v2.3|Done|kuroi-usagi|
|Ratmen|v2.12|Done|Darguth|
|Rift Daemons|v2.8|Done|cartag|
|Saurians|v2.8|Done|Darguth|
|Shadow Stalkers|v2.2|Done|Darguth|
|Sky-City Dwarves|v2.7|Done|Darguth|
|Vampiric Undead|v2.8|Done|Darguth|
|Volcanic Dwarves|v2.8|Done|kuroi-usagi|
|Wood Elves|v2.7|Done|Darguth|

## Reporting an issue

If you find something wrong with any of the existing army lists, please open a
Github issue so that myself or the owner of that file can address it.

# Credits

Scott Prutton for creation and maintenance of the repo and build infrastructure.
Darguth, cartag, Perram and kuroi-usagi for army catalog authorship.
