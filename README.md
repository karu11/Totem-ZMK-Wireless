<h1>Wireless Totem ZMK Config</h1>

Tried to include every ZMK dongle in this repository. Thanks to Eiga for the reference and all the dongle creators.


### Steps

## Fork or Clone Repository
   - Click **Fork** in the top right to copy this repo to your GitHub account, or
   - Run `git clone` locally.

   > Forking is recommended, because GitHub Actions will automatically build your firmware.

## Keymap Editing
   -  use the [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/):
     - Map your repository to the editor to see the current settings
     - Make changes on the site and save
     - your repository will be compiling the build with your new configuration
     - read below on flashing your keyboard

## Dongle Flashing
   - Turn all devices off
   - go to **Actions → your latest run → Artifacts** and download the firmware (`.uf2`) files.
   - Flash the dongle with the **appropriate** `settings_reset` file.
   - Flash the dongle controller with the `dongle` file.
   - Flash the first half with the the `settings_reset` file.
   - Flash the first half with the `left` or `right` files.
   - Repeat last two steps for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!


<img alt="image" src="https://github.com/user-attachments/assets/a28723b1-9afe-4b1d-aac8-1d9bbecff9cb" />
