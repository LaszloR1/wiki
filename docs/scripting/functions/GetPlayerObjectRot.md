---
id: GetPlayerObjectRot
title: GetPlayerObjectRot
description: Use this function to get the object's current rotation.
tags: ["player"]
---

## Description

Use this function to get the object's current rotation. The rotation is saved by reference in three RotX/RotY/RotZ variables.

| Name     | Description                                                   |
| -------- | ------------------------------------------------------------- |
| playerid | The player you associated this object to.                     |
| objectid | The objectid of the object you want to get the rotation from. |
| &Float:X | The variable to store the X rotation, passed by reference.    |
| &Float:Y | The variable to store the Y rotation, passed by reference.    |
| &Float:Z | The variable to store the Z rotation, passed by reference.    |

## Returns

The object's rotation is stored in the specified variables.

## Examples

```c
GetPlayerObjectRot(playerid, objectid, RotX, RotY, RotZ);
```

## Related Functions

- [CreatePlayerObject](../functions/CreatePlayerObject.md): Create an object for only one player.
- [DestroyPlayerObject](../functions/DestroyPlayerObject.md): Destroy a player object.
- [IsValidPlayerObject](../functions/IsValidPlayerObject.md): Checks if a certain player object is vaild.
- [MovePlayerObject](../functions/MovePlayerObject.md): Move a player object.
- [StopPlayerObject](../functions/StopPlayerObject.md): Stop a player object from moving.
- [SetPlayerObjectPos](../functions/SetPlayerObjectPos.md): Set the position of a player object.
- [SetPlayerObjectRot](../functions/SetPlayerObjectRot.md): Set the rotation of a player object.
- [GetPlayerObjectPos](../functions/GetPlayerObjectPos.md): Locate a player object.
- [AttachPlayerObjectToPlayer](../functions/AttachPlayerObjectToPlayer.md): Attach a player object to a player.
- [CreateObject](../functions/CreateObject.md): Create an object.
- [DestroyObject](../functions/DestroyObject.md): Destroy an object.
- [IsValidObject](../functions/IsValidObject.md): Checks if a certain object is vaild.
- [MoveObject](../functions/MoveObject.md): Move an object.
- [StopObject](../functions/StopObject.md): Stop an object from moving.
- [SetObjectPos](../functions/SetObjectPos.md): Set the position of an object.
- [SetObjectRot](../functions/SetObjectRot.md): Set the rotation of an object.
- [GetObjectPos](../functions/GetObjectPos.md): Locate an object.
- [GetObjectRot](../functions/GetObjectRot.md): Check the rotation of an object.
- [AttachObjectToPlayer](../functions/AttachObjectToPlayer.md): Attach an object to a player.
