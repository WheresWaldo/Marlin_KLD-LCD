Printer Information
===================
Fork from WheresWaldo/Marlin_KLD-LCD where limiting machine definitions are adapted to the (late March 2017) YHD-101 using Photonic3D which tries to move the build plate faster than the hardware accepts.

No guarantee that it will work on any other printer though these changes should work on anything that accepts WheresWaldo's Marlin_KLD-LCD.

For further information check the master https://github.com/WheresWaldo/Marlin_KLD-LCD

Configuring and compilation:
============================

Install the arduino software IDE/toolset v1.6.8 or newer
   http://www.arduino.cc/en/Main/Software

Copy the Marlin firmware
   https://github.com/bringho/Marlin_KLD-LCD
   (Use the download button)

Start the arduino IDE.
Select Tools -> Board -> Arduino Mega 2560 or your microcontroller
Select the correct serial port in Tools ->Serial Port
Open Marlin.ino

Click the Verify/Compile button

Click the Upload button
If all goes well the firmware is uploading
