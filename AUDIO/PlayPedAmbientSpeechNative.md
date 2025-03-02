---
ns: AUDIO
aliases: ["_PLAY_AMBIENT_SPEECH1"]
apiset: client
---
## PLAY_PED_AMBIENT_SPEECH_NATIVE

```c
// 0x8E04FEDD28D42462
Any PLAY_PED_AMBIENT_SPEECH_NATIVE(Ped speaker,Any* params);
```

struct ScriptedSpeechParams
{
	const char* speechName;
	const char* voiceName;
	alignas(8) int variation;
	alignas(8) Hash speechParamHash;
	alignas(8) Ped listenerPed;
	alignas(8) BOOL syncOverNetwork;
	alignas(8) int v7;
	alignas(8) int v8;
};

static_assert(sizeof(ScriptedSpeechParams) == 0x40, "incorrect ScriptedSpeechParams size");


Example:

ScriptedSpeechParams params{"RE_PH_RHD_V3_AGGRO", "0405_U_M_M_RhdSheriff_01", 1, joaat("SPEECH_PARAMS_BEAT_SHOUTED_CLEAR"), 0, true, 1, 1};
PLAY_PED_AMBIENT_SPEECH_NATIVE(PLAYER_PED_ID(), (Any*)&params);

Old name: _PLAY_AMBIENT_SPEECH1
https://github.com/femga/rdr3_discoveries/tree/master/audio/audio_banks

## Parameters
* **speaker**:
* **params**:

## Return value