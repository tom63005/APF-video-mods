# APF-video-mods
APF-M1000-MP1000-video-mods

These are my notes, primitive circuits, etc.

The APF console used the MC6847.
- - The MC6847 uses a 3.79545 MHz input. (datasheet/notes).
- - The outputs are white-level and color-phases.

The 3.8 Mhz is not a dot-clock.
- There are two capactiors in the MC1372 datasheet (see QUCS analysis)
- The capacitors are in the "quadrature encoder" circuit.
- We can get the 'raw video' but at a low level.

The dot-clock is from the MC6847 internal divider, as are the horizontal and vertical sync pulses.
- The sync pulses are internally added to the white-level output pin.

There is a "hairball" circuit... whazzat and how does it work ?

The BackGammon game does the 'bit-flutter' to create RED for Hearts and Diamond card-suits.
- - show the analysis of that and what the S-Video would look like.
  - Audio is an also-ran, but cover it just the same...

==END==
