# lily58-keymap
## Instructions
```shell
qmk setup

cd qmk_firmware/keyboards/lily58/keymaps

git clone https://github.com/ChinoGoblino/lily58-keymap.git

cd lily58-keymap

# Make sure keyboard controller mounted with correct permissions
qmk flash -c -kb lily58 -km lily58_keymap -e CONVERT_TO=helios

# repeat above with other controller
```
