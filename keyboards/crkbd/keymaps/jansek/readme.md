Install QMK with brew:
```bash
brew install qmk/qmk/qmk
```

Clone this repo:

```bash
git clone git@github.com:C-Jansek/qmk_firmware.git
```

Setup QMK with this repository:
```bash
qmk setup C-Jansek/qmk_firmware -H ~/path/to/qmk_firmware
```

Go into Jansek dir:
```bash
cd keyboards/crkbd/keymaps/jansek
```

Write json 2 config:
```bash
qmk json2c -o keymap.c jansek.json
```

Flash onto keyboard