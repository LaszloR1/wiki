---
id: GetPlayerVirtualWorld
title: GetPlayerVirtualWorld
description: Retrieves the current virtual world the player is in.
tags: ["player"]
---

## Description

Retrieves the current virtual world the player is in.

| Name     | Description                                       |
| -------- | ------------------------------------------------- |
| playerid | The ID of the player to get the virtual world of. |

## Returns

The ID of the virtual world the player is currently in.

## Examples

```c
public OnPlayerCommandText(playerid, cmdtext[])
{
    if(!strcmp(cmdtext, "/world", true))
    {
        new string[32];
        format(string, sizeof(string), "Your virtual world: %i", GetPlayerVirtualWorld(playerid));
        SendClientMessage(playerid, 0xFFFFFFFF, string);
        return 1;
    }
    return 0;
}
```

## Notes

:::tip

Virtual worlds are not the same as interiors.

:::

## Related Functions

- [SetPlayerVirtualWorld](../functions/SetPlayerVirtualWorld.md): Set the virtual world of a player.
- [GetVehicleVirtualWorld](../functions/GetVehicleVirtualWorld.md): Check what virtual world a vehicle is in.
- [GetPlayerInterior](../functions/GetPlayerInterior.md): Get the current interior of a player.
