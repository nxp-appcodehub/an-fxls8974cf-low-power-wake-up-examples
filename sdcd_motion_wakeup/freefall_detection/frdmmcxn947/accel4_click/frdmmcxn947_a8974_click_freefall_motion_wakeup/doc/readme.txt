Example Brief:
===================
This ISSDK FXLS8974CF example demonstrates SDCD configuration for freefall detection wake-up and enabling
auto-wake/sleep (AWS) feature to autonomously transition sensor to sleep mode on expiry of ASLP counter.

Hardware requirements
===================
- Mini/micro C USB cable
- FRDM-MCXN947 board
- Accle 4 Click board
- Personal Computer

Prepare the Demo
===============
1.  Connect a USB cable between the host PC and the MCU-Link USB port on the target board.
2.  Open a serial terminal with the following settings:
    - 115200 baud rate
    - 8 data bits
    - No parity
    - One stop bit
    - No flow control
3.  Download the program to the target board.
4.  Either press the reset button on your board or launch the debugger in your IDE to begin running the demo.

Running the demo
===============
Show a freefall on the board to detect freefall motion event. Make sure to not loose the MCU Link connection.
When the demo runs successfully, you can see the Samples printed to the terminal.

 ISSDK FXLS8974CF Example: Wake-Up on Freefall Detection & AWS
 Successfully Initialized Timandra with WHO_AM_I = 0x86
 Successfully Applied FXLS8974 SDCD Configuration for Freefall Detection

 ASLP (Auto Sleep) counter expired....
 Sensor Operating Mode Transitioned to Sleep Mode....SYSMODE = 2
 Putting MCU in low power sleep

 Freefall Motion Detected by Sensor SDCD Block....
 Sensor Operating Mode Transitioned to Wake Mode....SYSMODE = 1
 MCU Woke-up on Freefall Motion Event
 Will enter sleep mode after expiration of ASLP counter = ~5sec

 ASLP (Auto Sleep) counter expired....
 Sensor Operating Mode Transitioned to Sleep Mode....SYSMODE = 2
 Putting MCU in low power sleep

