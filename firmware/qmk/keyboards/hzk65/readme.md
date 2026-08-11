# hzk65

*Modular assembly 65% keyboard*

* Keyboard Maintainer: [Josu](https://github.com/josugoar)
* Hardware Supported: *hzk65*
* Hardware Availability: *https://github.com/josugoar/hzk65*

Make example for this keyboard (after setting up your build environment):

    make hzk65:default

Flashing example for this keyboard:

    make hzk65:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

> [!NOTE]
> The hzk65 keyboard directory must be copied to the [qmk_firmware](https://github.com/qmk/qmk_firmware) source tree for compilation

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
