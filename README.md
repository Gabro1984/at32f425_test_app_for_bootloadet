Simple application to test bootloader
======================================

Start FLASH address: 0x80005000 <br />
Tested on an unknbown Chinees board. <br />
The board differ from original AT-START-F425 by EXT XTAL frequency(used 12Mhz XTAL) and LEDx GPIOs. <br />
To use with original AT-START-F425 board use the definition AT_START_F425_V1 instead AT_TAOBAO_F425. <br />

Note: to bild app used cmake. GNU toolchain must be installed, path to GNU binaries must be added to PATH.
