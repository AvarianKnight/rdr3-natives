---
ns: PED
apiset: client
---
## GET_PED_LOOT_STATUS_MP

```c
// 0xC737697C41628340
int GET_PED_LOOT_STATUS_MP(Ped ped);
```

enum ePedLootStatus
{
	PLS_NONE,
	PLS_PRE_LOOT,
	PLS_SAMPLING,
	PLS_SKINNING
};

## Parameters
* **ped**:

## Return value