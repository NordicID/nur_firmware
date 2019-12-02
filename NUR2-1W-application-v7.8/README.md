2019/11/11  NUR2_APP_7.8_A
- Fixed slow command handling during streaming
- Improved Sec chip NVM update
- Calibration values backed up on host NVM
- Corrupted packet resend request mechanism added
- Indonesian frequencies changed
- Gen2v2 command support 
	- optional commands Authenticate, Untraceable and Blockpermalock added
	- requires sec chip release 3.3.0.0
- IRQ handling improvements

2019/11/11 SecChip_3.3.0.0
- Added support for Gen2v2 commands Authenticate, Untraceable and Blockpermalock
	- requires at least NUR2_APP_7.8_A release
- Buffer handling improvements
