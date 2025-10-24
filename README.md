zmk-keymap
==========
This repository is for .keymap and .json files used as input to creating firmware for various keyboards.
- .keymap: Devicetree keymap source (DTS/DTSI)
- .json: 
  - MoErgo [my.glove80.com](https://my.glove80.com) internal (not the same as ZMK Studio)
  - [ZMK studio](https://zmk.studio) layout

note:
- Only the .json files are supported for import by the MoErgo [my.glove80.com](https://my.glove80.com) web application.
    - my.glove80.com is dependent on .json instead of .keymap for file imports (not the same as ZMK Studio).
- Only the .keymap files are supported for import by the Nick Coutsos [keymap-editor](https://nickcoutsos.github.io/keymap-editor/) web application.
- The keymap.json is read when running locally (ENABLE_DEV_SERVER environment variable).

converting between .keymap and .json:
It is one way from .keymap to .json for ZMK Studio.

applications:
- MoErgo [my.glove80.com](https://my.glove80.com)
- Nick Coutsos [keymap-editor](https://nickcoutsos.github.io/keymap-editor/)
- [ZMK studio](https://zmk.studio)

repositories:
- MoErgo
    - moergo-sc-[glove80-zmk-config](https://github.com/moergo-sc/glove80-zmk-config)
    - moergo-sc-[glove80-zmk-config-west](https://github.com/moergo-sc/glove80-zmk-config-west)
    - moergo-sc-[zmk](https://github.com/moergo-sc/zmk)
    - MoErgo [Creating a ZMK config repo and building ZMK firmware the “traditional way”](https://docs.moergo.com/glove80-user-guide/appendix-zmk/#creating-a-zmk-config-repo-and-building-zmk-firmware-the-traditional-way)
- sunaku (Glorious Engrammer)
    - sunaku-[glove80-keymaps](https://github.com/sunaku/glove80-keymaps)
    - sunaku-[glove80-zmk-config](https://github.com/sunaku/glove80-zmk-config)
- zmk
- Keyboardhoarders
    - keyboardhoarders-[zmk-config-corne](https://github.com/KeyboardHoarders/zmk-config-corne)
- Kinesis
    - kinesis-[Adv360-Pro-ZMK](https://github.com/KinesisCorporation/Adv360-Pro-ZMK)
- Nick Coutsos
    - nickcoutsos-[keymap-editor](https://github.com/nickcoutsos/keymap-editor)

my forks:
- [moergo-sc-zmk](https://github.com/rovrevik/moergo-sc-zmk)
- [moergo-sc-glove80-zmk-config](https://github.com/rovrevik/moergo-sc-glove80-zmk-config) (generated from template)
- [moergo-sc-glove80-zmk-config-west](https://github.com/rovrevik/moergo-sc-glove80-zmk-config-west) (generated from template)
- [sunaku-glove80-keymaps](https://github.com/rovrevik/sunaku-glove80-keymaps)
- todo: [keyboardhoarders-zmk-config-corne](https://github.com/rovrevik/keyboardhoarders-zmk-config-corne)
- [kinesis-Adv360-Pro-ZMK](https://github.com/rovrevik/kinesis-Adv360-Pro-ZMK)
- todo: [zmk-keymap](https://github.com/rovrevik/zmk-keymap)
