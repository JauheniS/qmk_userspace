# BM60 Poker 60% "Usable60" (Windows, Linux and MacOS layouts)

![BM60HSRGB_poker](https://i.imgur.com/OzxCrGb.png)

A 60% hotswap inswitch RGB (north facing) keyboard from KP Republic.

This firmware make it usable for multi-system setups and programming aswell as supports MacOS.

* "Usable60" UserSpace Maintainer: [JauheniS](https://github.com/JauheniS)

* Keyboard Maintainer: [bdtc123](https://github.com/bdtc123)
* Hardware Supported: BM60HSRGB_Poker/rev2
* Hardware Availability: [KP Republic](https://kprepublic.com/products/bm60-rgb-poker-60-gh60-hot-swap-custom-mechanical-keyboard-pcb-program-qmk-underglow-type-c)

Make example (Windows and Linux) for this keyboard (after setting up your build environment):

    make kprepublic/bm60hsrgb_poker/rev2:JauheniS

Make example (MacOS) for this keyboard:

    make kprepublic/bm60hsrgb_poker/rev2:JauheniS_macos

Add-ons:

* Purple-colored Caps Lock when pressed
* ~ is Shift + Esc or Fn + Shift + Esc
* Fn key (1st layer):

    Back slash is BOOT
    ESC is GRAVE (` or ~)
    Backspace is DEL
    1 to + - f1-f12
    WASD are arrows
    Z changes RGB Mod
    X and C - Hue increase and decrease
    V and B - Saturation increase and decrease
    N and M - Value (Brightness) increase and decrease
    < and > - Page Up and Page Down
    /? - RGB Toggle on/off

* Right win works as 2nd layer switch

    Right Win + Left Win - Win Key lock toggle on/off

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
