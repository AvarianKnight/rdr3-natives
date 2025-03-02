---
ns: PED
aliases: ["0x92DAABA2C1C10B0E"]
apiset: client
---
## _UPDATE_PED_TEXTURE

```c
// 0x92DAABA2C1C10B0E
void _UPDATE_PED_TEXTURE(int textureId);
```

Should be called at least once for any new texture override.
Otherwise component textures will be just black.
Also needs to be called for updating any ped overlays to apply the changes.

## Parameters
* **textureId**:



