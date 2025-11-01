# Tchaikeebs

Teclado low profile 6x4 + 3 handwired totalmente impresso 3D PLA com logo do SPFC em baixo.

* Keyboard Maintainer: [guilhermesdm](https://github.com/guihermesdm)
* Hardware Availability: https://github.com/guilhermesdm/teclados/tchaikeebs

Make example for this keyboard (after setting up your build environment):

    make tchaikeebs:default

Flashing example for this keyboard:

    make tchaikeebs:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Physical boot button**: Hold BOOT button down and connect MCU to the PC
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
