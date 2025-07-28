# Cornedeon Keyboard
## Based on Corne Keyboard [CRKBD](https://github.com/foostan/crkbd)
Improved Corne 3 keyboard with full 4x6 matrix.

Keyboard Maintainer: [alko](https://github.com/alko-kbd) [alko-kbd@alk0.ru](mailto:alko-kbd@alk0.ru)
Hardware Supported: Corne 3 PCB, Handwired

![Corne3-based Cornedeon](https://cornedeon.ru/img/cornedeon_3_overviev.jpg)

Build:

qmk compile -kb alko/cornedeon/rev2 -km vial

Note: by default, almost all optional options are disabled in the keymaps/vial/rules.mk for compatibility with rev1_5 (atmega32u4). Configure it before building rev2 (rp2040).
