title: Alleyways

Inspired by "Lovers and Dancers", solve mysteries and make friends.

## Overview

Players play using an app on a device capable of detecting the proximity of other app-bearing devices in range. When near another player, the app reports to both players that they're close to another player. Ideally, the app provides a mechanism for finding the other player. 

When players meet, they can share "clues", which advance both players' "investigations". Prior to sharing these clues, they are not known to either player. Each player's app then remembers the other's "alias" in the "rolodex"; in the future, when these players are in range of each other, the app will report them by alias, rather than as just another player. Two players cannot share clues more than once every 24hr.

When a player finishes an investigation, the next clue they get begins the next one.

## Terms

* clue: a vignette of less than 120 characters, indicating an alibi, motive, or other pertinent detail of a character in the investigation. Clue length is limitted for tweeting.
* investigation: a finite but arbitrarily long collection of clues, beginning with the crime and ending with apprehending the perp.
* alias: a player's unique game handle.
* rolodex: a collection of all known aliases.

## Content questions

* How are new investigations/clues generated? By us, or the user, or both?

## Software questions

* How will players protect their identities when they want to revoke another player's knowledge of their alias?
* How will players hide from others they don't want to interact with?
* How will players find one another when they're informed another player is close?

## Hardware-dependent questions

* How will app-bearing devices detect one another?
* At what range will app-bearing devices report that other players are nearby?
* How will user data be stored, so as to protect identities while also collecting meaningful analytics?
  - Ideally, devices are independent of any central server, so we never have sensitive data.