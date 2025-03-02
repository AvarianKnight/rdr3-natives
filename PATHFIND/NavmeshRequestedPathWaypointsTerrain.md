---
ns: PATHFIND
aliases: ["0xF61CFEDEAB627BFA"]
apiset: client
---
## _NAVMESH_REQUESTED_PATH_WAYPOINTS_TERRAIN

```c
// 0xF61CFEDEAB627BFA
int _NAVMESH_REQUESTED_PATH_WAYPOINTS_TERRAIN(int path);
```

Returns a bit flag for seemingly terrain within the waypoints in the path. Checked against bit value 2 to match water in the path, seems to always contain at least 1 though regardless of location/ped.

## Parameters
* **path**:

## Return value

