---
ns: PED
apiset: client
---
## SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE

```c
// 0x7A6535691B477C48
void SET_PED_CAN_BE_KNOCKED_OFF_VEHICLE(Ped ped,int state);
```

state:
enum eKnockOffVehicle
{
	KNOCKOFFVEHICLE_DEFAULT,
	KNOCKOFFVEHICLE_NEVER,
	KNOCKOFFVEHICLE_EASY,
	KNOCKOFFVEHICLE_HARD
};

## Parameters
* **ped**:
* **state**:



