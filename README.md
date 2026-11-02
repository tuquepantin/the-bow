# The Bow

An interactive recreation of the bow-stringing scene from Christopher Nolan's *The Odyssey*. Press and hold to string the bow as the tension builds, then release to play the string and hear the final chord.

**Live:** https://tuquepantin.github.io/the-bow/

## How it works

1. **Press and hold** (mouse, long press or the space bar). The archer hooks the string onto the bow while the music plays (G + B♭, then E♭), and draws it back on the final D.
2. When the bow is fully strung, it trembles and a heartbeat speeds up.
3. **Release** to play the string: the final G–C chord rings out.

Sound starts after the first tap, since browsers block audio until the visitor interacts with the page. The on-screen text adapts automatically to the visitor's browser language.

## Built with

- Plain HTML, CSS and JavaScript in a single file, with no build step
- Canvas 2D for the bow, string and atmosphere
- Web Audio API for playback, reverb, echo and the tense background drone
- Nylon guitar samples from the MusyngKite soundfont ([midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts))
- Archer figure from a public-license SVG, styled after Greek red-figure pottery

This is a fan-made recreation and is not affiliated with the film or its studio.
