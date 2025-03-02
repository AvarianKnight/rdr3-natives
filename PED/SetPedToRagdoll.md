---
ns: PED
apiset: client
---
## SET_PED_TO_RAGDOLL

```c
// 0xAE99FB955581844A
BOOL SET_PED_TO_RAGDOLL(Ped ped,int timeMin,int timeMax,int ragdollType,BOOL abortIfInjured,BOOL abortIfDead,const char* nmTaskMessageParameterName);
```

nmTaskMessageParameterName: See physicstasks.ymt. Search for DraggedByCart or 0xD00820D7 (Used in R* SP Script marston8)

## Parameters
* **ped**:
* **timeMin**:
* **timeMax**:
* **ragdollType**:
* **abortIfInjured**:
* **abortIfDead**:
* **nmTaskMessageParameterName**:

## Return value