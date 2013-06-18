TweetMyPants
====================

An LED belt buckle for the Internet of Things... and the party in my pants.

Resources
---------------------
###Hardware:

- One Arduino (Uno or Mega should be suitable for prototyping, down the line we may want to upgrade to a smaller form factor, a la Arduino Pro)
- LED or LCD display such as [this one (LED)](http://www.adafruit.com/products/555), [this one (LCD)](http://www.adafruit.com/products/398), or [this one (OLED)](http://www.adafruit.com/products/823)
- Bluetooth module such as [this one](https://www.sparkfun.com/products/10253) or [the MacGyver version](http://www.instructables.com/id/Cheap-2-Way-Bluetooth-Connection-Between-Arduino-a/)
- Power supply

###Software:

As I envision it, there would be 2-3 parts to the system
- The hardware, which communicates over bluetooth with...
- A piece of software running on a phone — this fetches the tweets periodically and relays them to the hardware via bluetooth
- Possibly a web frontend and/or backend... frontend to send messages (unless we just want to link it directly to Twitter), backend to maybe do some tweet parsing to pass to the software.

This is naturally only one way of doing it. We could do it over WiFi with the right hardware, but if we want FULLY MOBILE PANTS... bluetooth may be the way to go?