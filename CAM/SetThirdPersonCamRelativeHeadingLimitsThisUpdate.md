---
ns: CAM
aliases: ["_CLAMP_GAMEPLAY_CAM_YAW"]
apiset: client
---
## SET_THIRD_PERSON_CAM_RELATIVE_HEADING_LIMITS_THIS_UPDATE

```c
// 0x14F3947318CA8AD2
void SET_THIRD_PERSON_CAM_RELATIVE_HEADING_LIMITS_THIS_UPDATE(float minimum,float maximum);
```

minimum: Degrees between -180f and 180f.
maximum: Degrees between -180f and 180f.

Clamps the gameplay camera's current yaw.

Eg. _CLAMP_GAMEPLAY_CAM_YAW(0.0f, 0.0f) will set the horizontal angle directly behind the player.

Old name: _CLAMP_GAMEPLAY_CAM_YAW

## Parameters
* **minimum**:
* **maximum**:



