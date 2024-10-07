# infynaught

4x3 macropad built with RP2040 compatible microcontrollers

* Keyboard Maintainer: [infynaught](https://github.com/infynaught)
* Hardware Supported: RP2040
* Hardware Availability: [RP2040](https://aliexpress.com/item/1005005616524430.html)

Make example for this keyboard (after setting up your build environment):

    make lcf_macro/default
    
Flashing example for this keyboard:

    make lcf_macro/default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs). Dont know how to make a handwire keyboard, check it out [SkottoKeebs handwire tutorial](https://www.youtube.com/watch?v=hjml-K-pV4E&pp=ygUTaGFuZHdpcmUgYSBtYWNyb3BhZA%3D%3D)

## Direct pin RP2040 

"GP2",  null,   null,   "GP3"
"GP4",  "GP5",  "GP6",  "GP7"
"GP8",  "GP9",  "GP10", "GP11"
"GP12", "GP13", "GP14", "GP15"

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (top left key) and plug in the keyboard
* **Physical reset button**: Double-press reset button
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available