# guitar-tones

Guitar tone configurations built in **Ableton Live 12 Lite**, with a
**Focusrite Scarlett 2i2 4th gen** as the interface.

## Structure

```
<Artist>/<Song>/       -> Ableton set + notes on the effect chain
_general-presets/      -> chains that don't belong to a specific song
```

Each folder holds the `.als` and a `README.md` with the exact value of every
device parameter, so the chain can be rebuilt by hand if needed.

## Base signal path

```
Guitar -> Input 1 (Inst) -> Scarlett 2i2 -> ASIO -> audio track in Live
```

In Live: an audio track with `Audio From: Ext. In / 1` and **Monitor = In**.

## What is not versioned here

Reference videos, reference audio and transcriptions. Only original
configurations go in. See `.gitignore`.
