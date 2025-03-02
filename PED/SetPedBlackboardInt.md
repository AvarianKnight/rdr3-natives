---
ns: PED
aliases: ["0x5F53010C4C3F6BAF"]
apiset: client
---
## _SET_PED_BLACKBOARD_INT

```c
// 0x5F53010C4C3F6BAF
void _SET_PED_BLACKBOARD_INT(Ped ped,const char* variableName,int value,int removeTimer);
```

https://github.com/femga/rdr3_discoveries/tree/master/AI/BLACKBOARDS
Blackboard natives allow you to apply and check certain data to/for peds.
Blackboard bools, floats and strings are subdivided into 6 sections: "all", "animation", "any", "code", "global" and "script"
Most changes are only visible for "script" blackboards, some "script" blackboards change ped motions
"removeTimer" is self-removal timer, can be "-1" so your data will not be removed by the game (forever); 100 = 1 second

## Parameters
* **ped**:
* **variableName**:
* **value**:
* **removeTimer**: