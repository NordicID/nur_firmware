2018/11/01      NUR2_APP_7.2_A
- Added NXP UCODE8 tag Brand ID support (needs at least sec chip v3.0.0.3)
- Added Custom Exchange command support (needs at least sec chip v3.0.0.3)
- Added multiple command parameter validity checks
- Added secondary chip version number to DevCaps message
- Fixed incorrect MODULE type in FWINFO cmd

**NOTE: For secondary chip update, Nordic ID RFID Confidgurator v1.8.2 (or newer) is needed.


2018/08/20		NUR2_APP_7.1_A
- Added extended carrier command support
- Added secondary chip programming support
- Added south africa region
- Added AR62 support
- Added Taiwan region support
- Added Reset to target command support
- Added custom hop table command support
- Added Monza QT commands
- Added support for power save options (nurapi period setup)
- Fixed Inventory ERROR_NO_TAG reported when last antenna did not see any tags, but previous one(s) did
- Fixed RSSI might be reported 0 when doing inventory read command
