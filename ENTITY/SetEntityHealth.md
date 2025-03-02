---
ns: ENTITY
aliases: ["_SET_ENTITY_HEALTH"]
apiset: client
---
## SET_ENTITY_HEALTH

```c
// 0xAC2767ED8BDFAB15
void SET_ENTITY_HEALTH(Entity entity,int healthAmount,Entity entityKilledBy);
```

Sets the entity's health. healthAmount sets the health value to that, and sets the maximum health core value. Setting healthAmount to 0 will kill the entity. entityKilledBy parameter can also be 0

## Parameters
* **entity**:
* **healthAmount**:
* **entityKilledBy**:



