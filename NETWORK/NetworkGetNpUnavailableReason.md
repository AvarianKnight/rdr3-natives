---
ns: NETWORK
aliases: ["0x74FB3E29E6D10FA9"]
apiset: client
---
## NETWORK_GET_NP_UNAVAILABLE_REASON

```c
// 0x74FB3E29E6D10FA9
int NETWORK_GET_NP_UNAVAILABLE_REASON();
```

Hardcoded to return zero.

==== PS4 specific info ====

Returns some sort of unavailable reason:
-1 = REASON_INVALID
 0 = REASON_OTHER
 1 = REASON_SYSTEM_UPDATE
 2 = REASON_GAME_UPDATE
 3 = REASON_SIGNED_OUT
 4 = REASON_AGE
 5 = REASON_CONNECTION

=================================


## Return value

