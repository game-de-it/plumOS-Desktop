

# plumOS-Desktop

<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc05.jpeg" width="320"> <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc06.jpeg" width="320"> <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc07.jpeg" width="320"> <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc08.jpeg" width="320">

plumOS-Desktop is a CFW based on dArkOS, designed specifically for the Powkiddy RGB30.
dArkOS is a handheld OS built on Debian Trixie.
[For more information about dArkOS, click here](https://github.com/christianhaitian/dArkOS)


## Acknowledgments
We would like to express our gratitude to the dArkOS development team.


## Notes

* Basic Linux knowledge is required to operate this CFW, so please study or research on your own to resolve any issues.
* Use a high-quality SD card.
* Using a slow SD card may cause the OS to run unstable.
* The OS may become unstable when switching between the desktop and Emulationstation.
* If the system becomes unresponsive, press the RGB30 reset button or hold down the power button to forcefully turn it off.
* While there may be requests or other bugs, there is generally no official support, so please resolve issues on your own.
* Do not contact the dArkOS author regarding this CFW.
* Using the OTA function may corrupt your OS environment, so use it with caution.

## Features

* Desktop environment powered by lightdm and LXQt.
* Watch YouTube videos in a browser or play music files.
* The RGB30 controller can be used for mouse operations.
* Supports USB mouse and USB keyboard.

  * Connecting a USB-HUB to the OTG port can be convenient.
* Emulationstation is available, allowing you to play games on emulators supported by dArkOS.

## How to Use

| Key operation                 |                                            Explanation |
| :---------------------------- | -----------------------------------------------------: |
| Left analog stick             |                                      Move mouse cursor |
| Up/Down on right analog stick |                               Scroll screen vertically |
| D-pad                         | Scroll screen in all directions, move menu items, etc. |
| R1 button                     |                                             Left click |
| L1 button                     |                                            Right click |
| L2 + X                        |                               Launch software keyboard |
| A button                      |                                              Enter key |

## Login User Information

* Username: `ark`
* Password: `ark`

  * This user can be used for SSH connections and other access.

## How to Connect to Wi-Fi

1. Click the network icon at the top of the screen, then search for an SSID under `Available Networks` or manually enter one via `Create New Wi-Fi Network`.

   <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc04.jpeg" width="320">

2. Press the controller’s L2 + X buttons to open the `Onboard` icon in the top panel. Press L2 + X again to launch the software keyboard.

   <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc02.jpeg" width="320">

<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc03.jpeg" width="320">

3. Once the SSID and password are entered, it should automatically connect. If not, try restarting the OS.

## Switching Between Emulationstation and Desktop

1. Click the `ES` icon at the top of the screen to switch to Emulationstation (do not click repeatedly).

   <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc01.jpeg" width="320">

2. To switch back to the desktop from Emulationstation, run `Start_LXQt` from the `Ports` section.

## How to Launch Dungeon Antiqua 2

1. Copy the `dungeon-antiqua2.pyxapp` file to the `roms/pyxel` directory on the SD card.
2. On the desktop, double-click `dungeon-antiqua2.sh` and click `Execute`.
3. From Emulationstation, run `dungeon-antiqua2` from the `Ports` section.

## Additional Information

[For more details, refer to the dArkOS wiki](https://github.com/christianhaitian/arkos/wiki/Frequently-Asked-Questions---RGB30)

---

