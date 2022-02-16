SparkFun PoE to USB Power Supply
===========================================================

[![SparkFun PoE to USB Power Supply](https://cdn.sparkfun.com//assets/parts/1/8/2/4/4/18709-PoE_Power_Supply-01.jpg)](https://www.sparkfun.com/products/18709)

[*SparkFun PoE to USB Power Supply (SPX-18709)*](https://www.sparkfun.com/products/18709)

It can be difficult to get a wall-wart where you need it. The promise of PoE (power over ethernet) is great, but what if your device doesn't use ethernet? Perhaps you could mess with power injectors, but what if you've already got PoE available on your network? The PoE to USB Power Supply is like a USB wall wart for PoE. Get a PoE hub, run ethernet wherever you need it, plug the PoE to USB Power Supply in and you'll have 5V at 1A via a USB A connector.

The onboard PoE module supports 36V to 57V DC input and provides up to 1.8A (9W) output. While the module claims 1.8A, we've pushed it to 1.5A before the module hit 75C and the output began to sag below 4.5V. The PoE to USB Power Supply has 1.5KV isolation, thermal cut off, and short circuit protection. The PoE module requires a 100mA load at all times so the PoE Power Supply includes a 50 Ohm resistor to constantly load the module with 100mA. There's a cuttable jumper to remove this load if needed. At a 1A load we measured a low 20mVPP ripple at 200kHz.

Who doesn't need 3.3V as well? In addition to the 5V provided via USB we've added a 3.3V 600mA regulator as well that can be connected via PTH solder connections. This is handy for systems running directly at 3.3V.

Repository Contents
-------------------

* **/Hardware** - Eagle files

License Information
-------------------

This product is _**open source**_! 

Various bits of the code have different licenses applied. Anything SparkFun wrote is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
