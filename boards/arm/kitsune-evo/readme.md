# Kitsune

![Kitsune EVO](about:blank)

Kitsune EVO is a wireless 40% mechanical keyboard PCB that uses a novel layout of the same name. Designed to take 40% keyboards mainstream, learn more about the Kitsune boards and layout [here](about:blank)

* Keyboard Maintainer: [Christian Lau](https://github.com/duock)
* Hardware Supported: Kitsune EVO v1.0, v1.1
* Hardware Availability: [Artifact Creatives](about:blank)

Make examples for this keyboard (after setting up your build environment):

**default**:

    make artifact_creatives/kitsune:default

**via**:

Default via files can be found [here](https://github.com/the-via/qmk_userspace_via/tree/main/keyboards/artifact_creatives/kitsune/keymaps/via)

    make artifact_creatives/kitsune:via

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Unplug the keyboard > Hold the top left key (Esc) > Plug in the keyboard
* **Physical reset button**: Unplug the keyboard > Remove the spacebar keycap > Hold the push button on the PCB (SW1/ BOOT0) > Plug in the keyboard
* **Keycode in layout**: Tap the key mapped to `QK_BOOT` if it is available
