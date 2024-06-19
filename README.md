# zmk config

This is the configuration of my piano keyboard. The keymap is based on dvorak.

## TODO

The following aspects still need clarification:

- do I need `key_repeat` anymore?
- I want a normal shift key which I can use in both layers, which means that it should be there where the `key_repeat` currently is located
- if I have an own shift key than I dont need the alpha caps macro key too, so I free another key, which I could use for something too
- some of the rolls now will conflict, for example: l + d if quickly rolled will result in backspace which is not intended
- create a branch which has the corresponding mappings for the keys when used on a layout dvorak and not the standard en_us (QWERTY) layout
- fix the sys and other layers for the special characters
