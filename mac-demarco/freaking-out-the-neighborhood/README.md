# Freaking Out the Neighborhood - Mac DeMarco

Set: `freaking-out-the-neighborhood.als`

Warm, dark, heavily modulated clean tone. Almost no gain: the character comes
from the modulation and from rolling the treble back, not from distortion.

## Chain (track 3, in order)

| # | Device | Parameters |
|---|---|---|
| 1 | **Compressor** | Threshold **-16.2 dB** - Ratio **4:1** - Attack **5.47 ms** - Release **205 ms** |
| 2 | **Saturator** | Analog Clip - Drive **6.3 dB** - Output **-1.4 dB** - Dry/Wet 100% |
| 3 | **EQ Three** | Low **+2.2 dB** - Mid **0.0 dB** - High **-6.7 dB** - FreqLow **250 Hz** - FreqHi **2.50 kHz** |
| 4 | **Chorus-Ensemble** | Classic - Rate **1.92 Hz** - Amount **63%** - Feedback 0% - Dry/Wet **80%** |
| 5 | **Phaser-Flanger** | **Flanger** - Rate 2 Hz - Amount 100% - Dry/Wet **49%** - **bypassed by default** |
| 6 | **Reverb** | Dry/Wet **25%** - Decay 1.20 s |

## Switching between the parts of the song

The reference rig used a single modulation pedal with several algorithms, so the
parts differ mainly in which modulation is running and which pickup is selected.
Here that maps to toggling one device on or off:

| Part | Pickup | Modulation |
|---|---|---|
| Main lead line | position 2 (bridge + middle) | **Chorus on**, Flanger off |
| Rhythm chords | position 4 (neck + middle) | **Flanger on**, Chorus off |
| Outro solo | bridge only | **Chorus on**, Flanger off |

Toggle a device with the small circle at the left of its title bar.

The chorus sits at **80% wet**, close to full but not quite: keeping a little dry
signal is what makes it read as that seasick vibrato instead of a plain chorus.

## Why the tone is set this way

Reference settings for this sound describe a clean Fender-style amp with drive
around 2-3, bass 6, mid 5 and **treble deliberately rolled back to about 4**,
presence low, bright cap off. It is not a bright chimey clean; it is round and a
little dark. Hence the light Saturator, the +2 dB in the lows and the -6.7 dB
shelf from 2.5 kHz up.

Reverb is short and low in the mix, standing in for a spring tank.

## Fine tuning

- Not wobbly enough -> raise Chorus **Amount**, or push Dry/Wet toward 90%.
- Too seasick -> lower Dry/Wet to 60-65%.
- Wobble too fast or too slow -> **Rate** between 1.5 and 2.5 Hz is the useful range.
- Too bright -> lower EQ Three **High**, or move FreqHi down toward 2 kHz.
- Too clean and stiff -> raise Saturator **Drive** a couple of dB. Keep it low;
  this tone is not a distorted one.

Neck or middle pickup, tone knob rolled back slightly, single coils. Tuning
slightly flat is part of the character on the record.
