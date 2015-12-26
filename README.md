# esptool-wrapper
A wrapper to use esptool.py instead of esptool-ck on Arduino.

---

## Installing:

1. Open the Arduino15 folder:
  * OS X: `/Users/$USER/Library/Arduino15/`
  * Linux: `/usr/share/arduino15` or `$HOME/.arduino15`
  * Windows: Only God knows (if you're God, pleade make a PR to improve Readme).
2. Navigate to `packages/esp8266/tools/esptool/*/` where `*`is the esptool version.
3. Copy the path to that folder.
4. Run the install.sh script (it may need root privileges).
    bash install.sh "/path/to/arduino15/packages/esp8266/tools/esptool/version/" 
5. Enjoy the wrapper!

## Usage:
You won't notice any difference while using Arduino IDE ![https://cdn01.gitter.im/_s/ce5803b/images/emoji/smiling_imp.png](https://cdn01.gitter.im/_s/ce5803b/images/emoji/smiling_imp.png)
