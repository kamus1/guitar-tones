# guitar-tones

Guitar tone configurations built in **Ableton Live 12**, with a
**Focusrite Scarlett 2i2 4th gen** as the interface.

## Structure

```
<artist-slug>/<song-slug>/   -> Ableton set + notes on the effect chain
_general-presets/            -> chains that don't belong to a specific song
```

Folder names are lowercase hyphenated slugs, so paths stay clean in URLs and
on any filesystem (no spaces, no `&`).

Each folder holds the `.als` and a `README.md` with the exact value of every
device parameter, so the chain can be rebuilt by hand if needed.
