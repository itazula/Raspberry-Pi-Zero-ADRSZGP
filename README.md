# Raspberry-Pi-Zero-ADRSZGP
Notes for the Raspberry Pi Zero 用　GPS拡張基板　from AssemblyDesk, part of their 01 (ゼロワン series) See their site at https://github.com/bit-trade-one/RasPi-Zero-One-Series Specifically, the GPS board is listed on https://github.com/bit-trade-one/RasPi-Zero-One-Series But there is no documentation at this time on how to use it.

I bought a board-mounted GPS module that plugs directly into the GPIO pins on a Raspberry Pi Zero WH (W=Wireless, H=Header). 

The funny thing is there are no instructions! In fact, somebody was asking on AssemblyDesk's Github site whether any detailed information existed; see https://github.com/bit-trade-one/RasPi-Zero-One-Series/issues

So, my approach was to just plug the board in, and then hope I could succeed.

The necessary information was gleaned from the following sites:

https://learn.adafruit.com/adafruit-ultimate-gps-on-the-raspberry-pi/using-uart-instead-of-usb
https://blog.whatgeek.com.pt/2015/03/connect-a-gps-to-the-raspberry-pi/
https://raspberrypi.stackexchange.com/questions/28483/cgps-gps-timeout

Finally, after about 1.5 hours of effort, success.

It helped to have the background provided by a course I took, https://stackskills.com/p/build-your-own-gps-tracking-system-raspberry-pi-zero-w-20181/. 

And, once again, it reminded me of the value of even rudimentary facility with the unix/linux command line. "cat /dev/Serial0" anyone?
