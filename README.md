# Installing FluidSynth and Sound Fonts

* Install FluidSynth : `brew install fluid-synth --with-libsndfile`
* Install this soundfont : http://www.schristiancollins.com/generaluser.php

`ln n -f GeneralUser\ GS\ 1.471/GeneralUser\ GS\ v1.471.sf2 ~/.fluidsynth/default_sound_font.sf2`
`fluidsynth -ni ~/.fluidsynth/default_sound_font.sf2 test.mid`
`fluidsynth -ni ~/.fluidsynth/default_sound_font.sf2  Melydi/melydi/midi_utils/test7.mid -F Melydi/melydi/midi_utils/test_synth.wav -r 44100`