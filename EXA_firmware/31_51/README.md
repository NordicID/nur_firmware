## EXA31/51 firmware version history
##### VER 2.4.4	(23.11.2020)
- Fix missing trig down event while reading barcode
- Added vibration in HID mode for indicating successful read.
- Fixed hang issue while operating in HID mode.
- Added wathdog functionality

#### Bootloader 16
- Added wathdog functionality

##### VER 2.3.4	(3.10.2019)
- SetBLEName ext command is now AccEnumSensor causing name corrupr
- Ignored SetBLEName as it set automatically by device
- Auto repair if name already corrupted

##### VER 2.3.2 (29.5.2019)
- Added possibility to clear pairing list while connected by keeping button Unpair + Power key down at least 2 second.
- Fixed pairing icon appearing on android in to generic (formaly gamepad) if HID mode not enabled when using paired connection.

##### VER 2.2.9 (9.5.2019)
- Fixed barcode scan activate bug when using accessory command readBarcodeAsync without aiming preceeded.

##### VER 2.2.8 (17.1.2019)
- Increased NUR2 power-up fail timeout from 5 sec to 10 sec.
- Decreased "No connection timeout" from 6 min to 90 sec.
- NUR Module is powered all the time after boot for EXA51e. Idle timer (5min) still pending.


