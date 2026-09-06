# Acoustic guitar (approximation)

Set: `acoustic-guitar.als`

A chain that pushes an electric guitar toward an acoustic timbre using only
stock Live 12 Lite devices.

## Chain (track 3, in order)

| # | Device | Parameters |
|---|---|---|
| 1 | **Compressor** | Threshold **-16.5 dB** - Ratio **4:1** - Attack **4.16 ms** - Release **205 ms** |
| 2 | **Channel EQ** | Low **-3.3 dB** - Mid **-5.9 dB** (1.5 kHz) - High **+6.2 dB** |
| 3 | **Chorus-Ensemble** | Classic mode - Rate 0.90 Hz - Amount 50% - Dry/Wet **25%** |
| 4 | **Reverb** | Dry/Wet **30%** |

The reasoning: the compressor adds the sustain and body a clean electric lacks,
the EQ removes the nasal midrange of the pickup and adds string brightness, the
chorus imitates the slight detuning between the strings of an acoustic, and the
reverb supplies the body and the room.

## Limitation

This is an imitation built from EQ and effects, not a simulation. Live Lite
ships with no impulse response loader and no amp simulator. A magnetic pickup
never captures pick noise, body thump or top resonance, and no processing can
invent what never entered the signal.

To get closer: a free IR loader (NadIR by Ignite Amps, KeFIR by Kuassa) with
impulse responses made specifically to turn an electric into an acoustic. Note
that most "acoustic guitar IR" packs are meant for acoustics with piezo pickups
and will not work for this.

Technique helps too: neck pickup, tone all the way up, fingers or a thin pick.
