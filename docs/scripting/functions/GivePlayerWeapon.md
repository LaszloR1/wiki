---
id: GivePlayerWeapon
title: GivePlayerWeapon
description: Give a player a weapon with a specified amount of ammo.
tags: ["player"]
---

## Description

Give a player a weapon with a specified amount of ammo.

| Name     | Description                                 |
| -------- | ------------------------------------------- |
| playerid | The ID of the player to give a weapon to.   |
| weaponid | The ID of the weapon to give to the player. |
| ammo     | The amount of ammo to give to the player.   |

## Returns

1: The function was executed successfully.

0: The function failed to execute. This means the player is not connected.

## Examples

```c
GivePlayerWeapon(playerid, 26, 64); // Give playerid a sawn-off shotgun with 64 ammo
```

## Related Functions

- [SetPlayerArmedWeapon](../functions/SetPlayerArmedWeapon.md): Set a player's armed weapon.
- [GetPlayerWeapon](../functions/GetPlayerWeapon.md): Check what weapon a player is currently holding.
