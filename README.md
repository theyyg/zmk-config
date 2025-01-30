# zmk-config
ZMK Configurations

## Updating the Keyboard
1- Modify the *.keymap file in the config directory.
2- Commit the changes to the git repository and push to github.
3- Navigate to the (Actions tab)[https://github.com/theyyg/zmk-config/actions] for this repository on github.
4- On a successful build, download the firmware.zip from the Actions summary.
5- Connect only one side of the keyboard to usb.  Double press the RESET button to put the controller in bootloader mode.
6- Copy the appropriate side firmware *.uf2 to the "USB drive".  The bootloader will automatically flash the firmware, and restart.  The virtual USB drive will automatically be removed from the PC (and the explorer window will close.)
7- Connect only the other side and flash its firmware file.
