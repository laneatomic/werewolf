---
layout: page
title: Roles
permalink: /roles/
---

### Standard

All game modes have the below roles.

#### Villager
The Villager is the simplest and most common role. The basic Villager has no special powers.

Variations:  
Cursed Villager: The Cursed Villager reveals as a Werewolf to the Seer and the Oracle

#### Seer
The Seer may have one vision per night, revealing the role of another player. Be wary, because the vision may not always be true (e.g. Cursed Villagers reveal as a Werewolf to the Seer). To see someone, `/msg werewolf see <nickname>` where `<nickname>` is the nickname of the player you want to investigate.

#### Werewolf
The Werewolf's role is to kill someone every night, and also be the last person alive. To kill someone, `/msg werewolf kill <nickname>` where `<nickname>` is the nickname of the player you want to kill.

### Charmed

In addition to the standard roles, this game mode introduces the Piper.

#### Piper
The Piper's job is to charm everyone in the game, and will win the game if she is able to charm everyone before the wolf wins. Her win will take precedence over the wolf. The piper may charm two players per night. To charm players, use `charm <nickname> [and <nickname>]`.

### Foolish

The Foolish game mode introduces two new roles, the Oracle and the Fool. The Oracle replaces the Seer in this mode.

#### Oracle
Similar to the Seer, the Oracle may have one vision per night. However, they will only find out if the player is a Wolf or not. The same caveats apply as Seer (e.g. Cursed Villagers look like werewolves).

#### Fool
The Fool wants to die by the hands of the village. The Fool will win and the game will end if they are lynched during the day. If they are killed overnight, they will lose normally. The Fool is seen as a villager by the Seer and Oracle. If the Fool has a Lover (see below), they should instead try to survive for the dual win with the Lover. The Lover will *not* win if the Fool dies.

### Mad

This game mode introduces the Mad Scientist.

#### Mad Scientist
If the Mad Scientist dies for any reason other than idling out or quitting, they throw a potion that kills the players who joined immediately before and after them (if they're still alive). The Mad Scientist is seen as a Wolf by the Seer and Oracle, despite being a Villager.

###