# dongle_256
Split BLE low profile keyboard using Nordic nRF52840 dongle PCA10059

(WIP) Firmware guide

Flash new bootloader:

We need UF2 bootloader to support CircuitPython. The PCA10059 isn't shipped with UF2, hence we have to flash it.

Lastest UF2 bootloader should be listed at: https://github.com/adafruit/Adafruit_nRF52_Bootloader/releases (go to assets and find pca10059, download the hex file)

If you have a Raspberry Pi you can follow this guide to flash it. (Tested with Raspberry Pi 4)

https://www.rototron.info/circuitpython-nrf52840-dongle-openocd-pi-tutorial/

OR if you have an STLink-V2 debugger:

Install STLink driver:

https://www.st.com/en/development-tools/stsw-link009.html#get-software

Get and use OpenOCD with STLink:

https://github.com/seemoo-lab/openhaystack/wiki/Flashing-nRF-with-OpenOCD---ST-Link
