# Strudel Kits (/strudel-kits/main)

Sample kits/etc for strudel.cc for use by Deformat and anyone else
Work In Progress as I figure out how to use strudel.cc

If you have anything you would like to contribute
please feel free to contact using the various social links below

## Current Sections

Below is a list of the current kits available on this git

### Breaks (/breaks)

This section contains various breaks (sorted by type and bpm)
The following packs are avaiable:

**Amen** (/breaks/amen-180) 
**Oldschool** (/breaks/oldschool-180)

### Gabber Kicks (/gabber-kicks)

**GabberMaster** (/gabber-kicks/gabber-master)
    This entire subpackage has a multinstrument strudel.json
    This can be imported as one library, or each independantly.

    Contains:
    * merrik kick 1 (/gabber-kicks/gabber-master/merrikkick1)
    * merrik kick 2 (/gabber-kicks/gabber-master/merrikkick2)
    * merrik kick 1 (/gabber-kicks/gabber-master/merrikkick3)

### WAVE TABLES (/wt)

This section is generated wavetables, as well as morphing wavetables
These are all designed to be single cycle 16 bit wav with a 44100 sample rate 
 and 1024 samples per cycle

They were all generated with numpy, and the scripts used to generate them will
be included eventually.

**std** (/wt/std)
    Standard waveforms, basic

## Information Regarding Samples

### BitRate of Samples:

All samples will be in 44.1 kHz mono 16bit PCM 

### Mastering of Samples:

All samples will have a limited peak of -3db

### Why this?

Compatibility and usability. These parameters are usable on a wide variety of systems, 
even down to trackers written in the 90s. 
This will allow these samples to have use beyond strudel.cc. 
This instantly makes these samples usable on the OG Polyend Tracker without any conversion, 
and is also the format for bare_metal (a tracker which I am designing)

### Edge Cases:

In the event that sample packs do not meet this unified criteria, 
it will explicitly written in the README.md file, as well as be included in the name.
Stereo .wav files, or those with different sample rates will be expressed in both the 
readme as well as the name, example drum6-48k-str would be a drum6 kit, 
but sampled at 48k and in stereo.

This is done similarly to how breakbeats/loops (will) state the bar 
number in the case of not being a 2 bar long.

### Please Note:

This is a goal, not all work is perfect, and there is a chance some samples 
may have missed these standards, do not hesitate to contact if this is the 
case so it can be corrected.

## Whats Next/Todo

Add more packs
Add detailed descriptions to each pack
Attribute to each pack where applicable
More verbose descripotion to this README.md
Add links to each pack via markdown from this page

## Social Links

### Deformat
[Deformat Records – Website](https://www.deformatrecords.com/)  
[Deformat Records – Instagram](https://www.instagram.com/deformat.records/)  
[Deformat Records – Facebook](https://www.facebook.com/deformat.records/)  
[Deformat Records – YouTube](https://www.youtube.com/@deformat)

### Noise 4 Tots
[Noise 4 Tots – Website](https://www.deformatrecords.com/artist/noise-4-tots/)  
[Noise 4 Tots – Instagram](https://www.instagram.com/noise4tots/)  
[Noise 4 Tots – Facebook](https://www.facebook.com/noise4tots)  
[Noise 4 Tots – YouTube](https://www.youtube.com/@noise4tots)  