---
ns: PED
apiset: client
---
## _SET_PELT_FOR_HORSE_BY_INVENTORY_ITEM

```c
// 0xC412AA1C73111FE0
void _SET_PELT_FOR_HORSE_BY_INVENTORY_ITEM(Ped horse, Hash itemHash, Hash albedo, Hash normal, BOOL p4);
```

Set the pelt of the animal to the back of the horse
EXAMPLE:
local mount = GetMountOwnedByPlayer(PlayerId())
Citizen.InvokeNative(0xC412AA1C73111FE0,mount,GetHashKey('PROVISION_DEER_HIDE_POOR'),GetHashKey('a_c_deer_01_uppr_000_c0_001_ab'),0,0)

## Parameters
* **horse**:
* **itemHash**:
* **albedo**:
* **normal**:
* **p4**: