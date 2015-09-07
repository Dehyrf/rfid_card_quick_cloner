# rfid_card_quick_cloner
Clones mifare rfid cards with a PN532 NFC RFID module and an arduino. 

Set module to i2c and connect vcc to 5v, gnd to gnd, sda to A4 (uno) or sda (leonardo), scl to A5 (uno) or scl (leonardo).

Tap card to clone, wait for led flash, then put on a fresh card and wait a few seconds for slow pulse to indicate completion. Progress and found/flashed number output on serial @ 115200. Tested on uno, leonardo.
