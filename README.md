<h1>Wireless Totem ZMK Config</h1>

Tried to include every ZMK dongle in this repository.


### Steps

1. **Fork or Clone This Repository**
   - Click **Fork** in the top right to copy this repo to your GitHub account, or
   - Run `git clone` locally.

   > Forking is recommended, because GitHub Actions will automatically build your firmware.

2. **Edit Your Keymap**
   -  use the [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/):
     - Make changes on the site and save
     - your repository will be compiling the build with your new configuration
     - download the firmware when complete
     - **Actions → your latest run → Artifacts** and download the firmware (`.uf2`) files.
     - if you are using a dongle, upload the appropriate dongle file to your dongle for changes to be applied. Without a dongle, update the left and right accordingly.
  
3. **Build with GitHub Actions**
   - After pushing, GitHub Actions will automatically run the build.
   - Once the workflow finishes, go to **Actions → your latest run → Artifacts** and download the firmware (`.uf2`) files.

4. **Flash Your Keyboard**
   - Put your board into UF2 bootloader mode (usually by double-tapping the reset button).
   - Drag and drop the `.uf2` file onto the mounted drive.
  
### Dongles - If you feel like the dongle is no longer paired with the totems, use the reset files related to your dongle to clean slate your dongle and do the same with your totem using the totem reset file. then upload the files, dongle first then left and right units.

   
    <img src="https://raw.githubusercontent.com/karuetech/Totem-ZMK-Wireless-Firmware/bf551d05cbb7dbbcb7ba3f47e92db24be0b34730/keymap-drawer/totem.svg">

