# Matrix keyboard
This is my attempt at making a keyboard that is as compact as possible but still useable, meaning that all the letter keys are still where they should be (just ortholinear). The pcb design is in hardware as a kicad file or as the finished gerber files I needed for pcbway.

## Important
This is my first keyboard, it‘s not perfect. The pcb does not include an off switch or reset button since I didn‘t find them important, as I will be using the keyboard quasy always and it did not really degrade the battery life too much for me. If you try to build this keyboard, **add a reset button** since pairing is extremely difficult without one.

The files are adapted to me, the bottom keys for example are shifted by one since I always typed like that. Also one of my controllers was faulty so I had to add an additional pin that is not needed normaly (pin 101).

## Unimportant
Recently I found the [36 key keyboard by dilshod](https://github.com/dilshod/36-choc-key-ortholinear-split) which is basically the same keyboard but with better execution. I am also planning on making a new version / revision that uses the kailh PG1316S switches (that are not yet commonly available as far as I know) as seen in [mikeholschers mikefive](https://github.com/mikeholscher/zmk-config-mikefive) keyboard as they could potentially reduce the thickness greatly.

[Keymap editor by nickcoutsos](https://nickcoutsos.github.io/keymap-editor/)

## Final product
The keyboard looks like this, with an iPhone 11 for size comparison. 

![image of matrix keyboard](/matrix_keyboard.jpeg)
