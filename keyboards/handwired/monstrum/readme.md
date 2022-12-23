# Monstrum

This is fully custom designed and 3D printed keyboard using the Elite-C micro controller

## Wiring

I don't have a diagram and I couldn't be bothered to make one, so instead here are some photos and you can reference that with the monstrum.h file

![Photo of wiring 1](https://github.com/ONDRA5/qmk_firmware/blob/master/keyboards/handwired/monstrum/photos/wire_1.jpg)
![Photo of wiring 2](https://github.com/ONDRA5/qmk_firmware/blob/master/keyboards/handwired/monstrum/photos/wire_2.jpg)
![Photo of wiring 3](https://github.com/ONDRA5/qmk_firmware/blob/master/keyboards/handwired/monstrum/photos/wire_3.jpg)

## Flashing

Make example for this keyboard (after setting up your build environment):

    make handwired/monstrum:default

Flashing example for this keyboard:

    make handwired/monstrum:default:dfu

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader:

**Keycode in layout**: Press the key mapped to `QK_BOOT` (Fn+Del)

## Photos

![Photo_1](https://github.com/ONDRA5/qmk_firmware/blob/master/keyboards/handwired/monstrum/photos/front.jpg)
![Photo_2](https://github.com/ONDRA5/qmk_firmware/blob/master/keyboards/handwired/monstrum/photos/side.jpg)
