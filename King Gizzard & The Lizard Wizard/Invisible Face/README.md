# Invisible Face - King Gizzard & The Lizard Wizard

Set: `invisible-face.als`

An approximation of the main guitar timbre: amp-style fuzz, heavily
mid-forward, rolled-off highs, with modulation and delay underneath.

## Chain (track 3, in order)

| # | Device | Parameters |
|---|---|---|
| 1 | **Saturator** | Analog Clip - Drive **12 dB** - Output **-7.4 dB** - Dry/Wet 100% |
| 2 | **Saturator** | Analog Clip - Drive **22 dB** - Output **-7.4 dB** - Dry/Wet 100% |
| 3 | **EQ Three** | Low **-1.9 dB** - Mid **+6.0 dB** - High **-7.0 dB** - FreqLow **125 Hz** - FreqHi **1.90 kHz** |
| 4 | **Phaser-Flanger** | **Flanger** mode - Rate 2 Hz - Amount 100% - Feedback 0% - Dry/Wet **32%** |
| 5 | **Delay** | Synced **3/16** L and R - **Repitch** mode - Feedback 50% - Dry/Wet **15%** |
| 6 | **Reverb** | Dry/Wet **20%** - Decay 1.20 s |

Two saturation stages in series instead of one very hot stage: the first one
thickens, the second one dirties. That is how a real preamp + power amp behave.

## How it was calibrated

The average spectrum of 25 s of a reference video was measured (full mix, not an
isolated guitar) and the EQ was set against that curve:

| Band | Relative level |
|---|---|
| 63 Hz | -7.0 dB |
| 125 Hz | -4.3 dB |
| 250 Hz | -6.0 dB |
| **500 Hz** | **0.0 dB (peak)** |
| 1 kHz | -0.7 dB |
| 2 kHz | -7.5 dB |
| 4 kHz | -13.6 dB |
| 8 kHz | -23.7 dB |

Spectral centroid **693 Hz**. Crest factor **14.7 dB** - less compressed than it
sounds, which points to amp saturation rather than a squashed fuzz.

## Important limitation

*Flying Microtonal Banana* (2017) was played on guitars modified with extra
frets so they could play **quarter tones**. Those notes do not exist on a
standard fretboard and no effect can generate them: it is a physical
modification of the neck, not a sound.

Ways to get closer on a standard guitar:
- **Quarter-tone bends** (half of a semitone bend).
- Slide.
- Studio trick: duplicate the track with an **Auto Shift at -50 cents** mixed
  low underneath, to create the dissonant beating.

## Fine tuning

- Too harsh -> lower Drive on Saturator 2.
- Muddy -> lower Mid on EQ Three.
- Too bright -> lower High, or move FreqHi down toward 1.5 kHz.
- Too thin -> raise Low toward 0 dB.
- Lacking body -> raise Drive on Saturator **1** (not 2).

Use the neck or middle pickup. The bridge pickup adds a 2-3 kHz peak that the
EQ cannot fully tame.
