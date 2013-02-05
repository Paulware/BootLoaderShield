This [shield](https://www.tindie.com/shops/Paulware/bootloader-shield/) works well with the [DIY ARDUINO](https://www.tindie.com/shops/Paulware/diy-arduino/) available at tindie.
You will also need a [USB Programmer](https://www.tindie.com/shops/Paulware/usb-to-serial-programmer/) from tindie. 

The shield also works well with the Duemilanove but does not work with the UNO.

It was last tested with Arduino IDE Version 1.02

Here are the steps to use this device 
  * Assemble the pieces
![My image](https://github.com/Paulware/BootLoaderShield/raw/master/images/RequiredParts.jpg)

  * Connect the Programmer to the DIY Arduino and place the atmega328/atmega168 in the zero insertion force socket
![My image](https://github.com/Paulware/BootLoaderShield/raw/master/images/AlmostReady.jpg)

  * Place the populated shield in the DIY Arduino
![My image](https://github.com/Paulware/BootLoaderShield/raw/master/images/ReadyToRun.jpg)

  * Connect the usb serial programmer to your computer and upload the bootloader.ino sketch to the DIY Arduino
  
  * Select Tools->Board type you are going to flash with the bootloader ( Arduino Duemilanove w/ATmega328 or Duemilanove w/ATmega168)
  
  * Select Tools->Programmer->Arduino as ISP
  
  * Select Tools->Burn Bootloader

  * Here is a youtube video that goes through the steps 
  ![My tube](http://www.youtube.com/watch?v=82v-E5TkgYQ&feature=youtu.be)

  * To make a stand-alone devie, reference this simple drawing: 
  ![My drawing](https://github.com/Paulware/BootLoaderShield/raw/master/images/atmega328.jpg)

