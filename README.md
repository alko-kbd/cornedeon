# Cornedeon Keyboard
## Based on Corne Keyboard [CRKBD](https://github.com/foostan/crkbd)
Improved Corne 3 keyboard with full 4x6 matrix.

Keyboard Maintainer: [alko](https://github.com/alko-kbd) [alko-kbd@alk0.ru](mailto:alko-kbd@alk0.ru)

Site: [cornedeon.ru](https://cornedeon.ru)

Hardware Supported: Corne 3 PCB, Handwired

![Corne3-based Cornedeon](https://cornedeon.ru/img/cornedeon_3_overviev.jpg)

Build:

Prepare vial-qmk [environment](https://get.vial.today/docs/porting-to-vial.html).

Copy its into /keyboards/alko/cornedeon.

qmk compile -kb alko/cornedeon/rev2 -km vial

Note: by default, almost all optional options are disabled in the keymaps/vial/rules.mk for compatibility with rev1_5 (atmega32u4). Configure it before building rev2 (rp2040).
