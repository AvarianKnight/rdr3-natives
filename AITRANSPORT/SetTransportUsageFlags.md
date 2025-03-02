---
ns: AITRANSPORT
aliases: ["0xE2487779957FE897"]
apiset: client
---
## _SET_TRANSPORT_USAGE_FLAGS

```c
// 0xE2487779957FE897
void _SET_TRANSPORT_USAGE_FLAGS(Entity transportEntity,int flags);
```

enum eTransportUsageFlags
{
	TUF_INVALID = 0,
	TUF_ALLOW_DRIVER_ME = (1 << 0),
	TUF_ALLOW_DRIVER_GANG = (1 << 1),
	TUF_ALLOW_DRIVER_CREW = (1 << 2),
	TUF_ALLOW_DRIVER_FRIENDS = (1 << 3),
	TUF_ALLOW_DRIVER_ANYONE = (1 << 4),
	TUF_ALLOW_PASSENGER_ME = (1 << 5),
	TUF_ALLOW_PASSENGER_GANG = (1 << 6),
	TUF_ALLOW_PASSENGER_CREW = (1 << 7),
	TUF_ALLOW_PASSENGER_FRIENDS = (1 << 8),
	TUF_ALLOW_PASSENGER_ANYONE = (1 << 9),
	TUF_ALLOW_ACCESS_AI = (1 << 10)
};

## Parameters
* **transportEntity**:
* **flags**: