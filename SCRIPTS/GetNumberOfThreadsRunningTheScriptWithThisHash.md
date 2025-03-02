---
ns: SCRIPTS
aliases: ["_GET_NUMBER_OF_REFERENCES_OF_SCRIPT_WITH_NAME_HASH"]
apiset: client
---
## GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH

```c
// 0x8E34C953364A76DD
int GET_NUMBER_OF_THREADS_RUNNING_THE_SCRIPT_WITH_THIS_HASH(Hash scriptHash);
```

Gets the number of instances of the specified script is currently running.

Actually returns numRefs - 1.
if (program)
	v3 = rage::scrProgram::GetNumRefs(program) - 1;
return v3;

Old name: _GET_NUMBER_OF_REFERENCES_OF_SCRIPT_WITH_NAME_HASH

## Parameters
* **scriptHash**:

## Return value