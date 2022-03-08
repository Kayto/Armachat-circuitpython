# Armachat-circuitpython
New Armachat based on Raspberry Pi PICO an Circuitpython code

**Software working features:**

- send message with header and store to memory
- receive message and parse header, store to memory
- display message memory with message details like SNR and RSSI
- count messages in memory by type
- display some hw details like free memory and power supply voltage, it is good for future battery operation
- Terminal display with messages from background systems
- AES256 encryption
- message confirmation and status change in memory
- boot safe mode


**TODO:**

- Need much better LoRa libray with, CAD, status detection, and INTERUPT !!!
- contact list
- setup and save configuration
- save memory to flash

...

**Kayto Fork Notes**
- experimental comments in code to test writing to text files.
- added additional menu items - currently not developed.
- added cpu temp to information screen
- added a very rudimentary ping command - press 'p' to send a ping message. sends user name to reciever.

**Fixes in this repository**

- Much more stable
- Viewing messages after sending a message does not cause a crash
- Index issue fixed to prevent random crashes
- The boot.py file is setup for Compact version. Use previous version if using max version
- BTW: Save memory to flash does work if you change the file system to write mode by pressing the ALT key when booting and pressing the S key when viewing messages.
