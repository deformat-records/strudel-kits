# Morphing WaveTables (/wt/morph)

This section is generated morphing wavetables
These are all multiple cycle 16 bit wav with a 44100 sample rate
and 1024 samples per cycle.

Presently, this wave is 8 cycles long and encompasses the /wt/std wavetable.

## Whats in this pack

Contains:
    wt_morph.wav

It also contains a single strudel.json for loading it in.

## Usage example

In strudel, use this how you would any waveform:

// Import the samples:
samples ('github:deformat-records/strudel-kits/main/wt/std')

// Then play
$: note("<e4 g4 b4 <d5 <b5 g5>>>*16")
  .sound("wt_sine_saw").n("<1 2 3 4 5 6 7 8 9 10>/2").velocity(0.25).often(n => n.ply(2))
.release(0.125).decay("<0.4 0.4 0.3 0.4>")
  .cutoff(sine.range(500,5000).slow(8)).euclid(5,8)
  .gain(slider(1,0,1,0.01))