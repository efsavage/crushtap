CrushTap
==================

CrushTap is a Raspberry Pi-based hardware and software project that will let you monitor environmental conditions remotely via any web browser, including a mobile device.  Following these step-by-step instructions should get you up and running with no real electronics or software development background.  This is very much a DIY project so you will need some patience! 

  - [What You'll Need](#what-youll-need)
  - [Credits](#credits)
  - [CrushTap?](#name)
  
## What You'll Need

 - A Raspberry Pi 2 Model B, this will likely work with other models with little or no modification, but that is the reference for these instructions.
 - A USB Wi-Fi Adaptor or you can plug the Raspberry Pi in by Ethernet.  These instructions use the Edimax EW-7811Un 150Mbps 11n Wi-Fi USB Adapter.  
 - An HDMI-compatible display and a USB keyboard and mouse.  You will only need to perform the initial configuration of your Raspberry Pi. 
 - One or more DS18B20 Temperature Sensors, the waterproof style is recommended. 
 - A 4.7kΩ Resistor, 0.25W

## Raspberry Pi Setup

 - Run startx and get online by Wi-Fi[https://www.raspberrypi.org/documentation/configuration/wireless/] or Ethernet.
 - Run raspi-config and enable SSH.
 - Install node
 
## CrushTap Setup

 - Open an Terminal on the Raspberry Pi or SSH into it.
 - Check out this project: git clone git@github.com:efsavage/crushtap.git
 - cd crushtap
 
## Firebase Setup

 - Create a new Firebase account (they are free!).
 - Create a new App and remember the name of the app.

## Credits

 - Eric Savage

## CrushTap?

I started this project to monitor our tortoise, Crush! 