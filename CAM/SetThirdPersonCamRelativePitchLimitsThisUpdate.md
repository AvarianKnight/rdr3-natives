---
ns: CAM
aliases: ["_CLAMP_GAMEPLAY_CAM_PITCH"]
apiset: client
---
## SET_THIRD_PERSON_CAM_RELATIVE_PITCH_LIMITS_THIS_UPDATE

```c
// 0x326C7AA308F3DF6A
void SET_THIRD_PERSON_CAM_RELATIVE_PITCH_LIMITS_THIS_UPDATE(float minimum, float maximum);
```

minimum: Degrees between -90f and 90f.
maximum: Degrees between -90f and 90f.

Clamps the gameplay camera's current pitch.

Eg. _CLAMP_GAMEPLAY_CAM_PITCH(0.0f, 0.0f) will set the vertical angle directly behind the player.

Old name: _CLAMP_GAMEPLAY_CAM_PITCH

## Parameters
* **minimum**:
* **maximum**: