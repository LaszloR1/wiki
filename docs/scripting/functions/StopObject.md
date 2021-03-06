---
id: StopObject
title: StopObject
description: Stop a moving object after MoveObject has been used.
tags: []
---

## Description

Stop a moving object after MoveObject has been used.

| Name     | Description                          |
| -------- | ------------------------------------ |
| objectid | The ID of the object to stop moving. |

## Returns

This function does not return any specific values.

## Examples

```c
public OnGameModeInit()
{
    new obj;
    obj = CreateObject(...);
    return 1;
}
public OnPlayerCommandText(playerid, cmdtext[])
{
    if(strcmp(cmd, "/stopobject", true) == 0)
    {
        StopObject(obj);
        return 1;
    }
    return 0;
}
```

## Related Functions

- [CreateObject](../functions/CreateObject.md): Create an object.
- [DestroyObject](../functions/DestroyObject.md): Destroy an object.
- [IsValidObject](../functions/IsValidObject.md): Checks if a certain object is vaild.
- [MoveObject](../functions/MoveObject.md): Move an object.
- [SetObjectPos](../functions/SetObjectPos.md): Set the position of an object.
- [SetObjectRot](../functions/SetObjectRot.md): Set the rotation of an object.
- [GetObjectPos](../functions/GetObjectPos.md): Locate an object.
- [GetObjectRot](../functions/GetObjectRot.md): Check the rotation of an object.
- [AttachObjectToPlayer](../functions/AttachObjectToPlayer.md): Attach an object to a player.
- [CreatePlayerObject](../functions/CreatePlayerObject.md): Create an object for only one player.
- [DestroyPlayerObject](../functions/DestroyPlayerObject.md): Destroy a player object.
- [IsValidPlayerObject](../functions/IsValidPlayerObject.md): Checks if a certain player object is vaild.
- [MovePlayerObject](../functions/MovePlayerObject.md): Move a player object.
- [StopPlayerObject](../functions/StopPlayerObject.md): Stop a player object from moving.
- [SetPlayerObjectPos](../functions/SetPlayerObjectPos.md): Set the position of a player object.
- [SetPlayerObjectRot](../functions/SetPlayerObjectRot.md): Set the rotation of a player object.
- [GetPlayerObjectPos](../functions/GetPlayerObjectPos.md): Locate a player object.
- [GetPlayerObjectRot](../functions/GetPlayerObjectRot.md): Check the rotation of a player object.
- [AttachPlayerObjectToPlayer](../functions/AttachPlayerObjectToPlayer.md): Attach a player object to a player.
- [OnObjectMoved](../callbacks/OnObjectMoved.md): Called when an object stops moving.
