---
title: Friend List
nav: cofh-core
redirect_from:
  - /docs/cofh-core/friend-list/
---

The **friend list** is a feature that allows players to mark other players as
their friends. This can be used by blocks or items that are secured with a
[signalum security lock](/docs/signalum-security-lock/).


Management
----------

A player can manage their friend list using the [`/cofh friend`
command](/docs/cofh-core-commands/#friend).

While the command allows players to quickly add and remove other players, a
friend list can also be managed in a GUI by using `/cofh friend gui`. This GUI
consists of a text box with buttons to add or remove a player, a list of online
players and the friend list itself. Player names can be chosen from the lists,
or typed manually in the text box.

![Friend list GUI](/assets/images/cofh-core/friend-list-gui.png){:style="height: 250px"}


Usage
-----

When a block or item that is secured with a [signalum security
lock](/docs/signalum-security-lock/) is in 'Restricted' mode, the owner and
anyone in their friend list can access it.
