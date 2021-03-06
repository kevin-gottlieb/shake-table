# shake-table
Circuit diagram and Arduino Programs to build and operate an earthquake-simulating shake table. <br>
Built using Arudino Mega 2560 Rev 3 <br>
Feature list:
* Movement in X, Y, and Z axes
* 10 DC motors
* 16 low-power vibrating motors for aftershock simulation
* Multiple potentiometers for active control of shake power 
* Readout via LCD display (not shown on circuit diagram, but supported in Arduino code), multicolored LEDs, and a variety of audio tones
* Real-time clock 
* Bluetooth connectivity

All code needed to operate shake table inside shakeTableOperationCode. Specific tests for debugging are inside testCode. Include [RTC-Lib](https://github.com/adafruit/RTClib) to operate real-time clock <br>