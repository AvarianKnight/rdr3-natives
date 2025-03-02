---
ns: PLAYER
apiset: client
---
## _SET_PLAYER_AIM_WEAPON

```c
// 0xCFFC3ECCD7A5CCEB
void _SET_PLAYER_AIM_WEAPON(Player player,Hash weapon,int attachSlotId);
```

Sets the weapon that the specified player will aim with. The weapon must already be assigned to the PED. This also determines the weapon order, specifying which weapon the player will automatically switch to when the current weapon runs out of ammo.

## Parameters
* **player**:
* **weapon**:
* **attachSlotId**:



