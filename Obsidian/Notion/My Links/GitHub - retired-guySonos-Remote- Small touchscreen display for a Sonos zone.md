---
Created: 2021-12-06T13:23
URL: https://github.com/retired-guy/Sonos-Remote
---
# Sonos-Remote

Small touchscreen display for a Sonos zone

Tested on RPi Zero WH with Hyperpixel 4" touchscreen display

In order to run as the pi user to access the framebuffer, you'll need to add it to the video group:

usermod -a -G video pi

To start this at boot, create a service file and launch the Python script with it: [https://www.raspberrypi.org/documentation/linux/usage/systemd.md](https://www.raspberrypi.org/documentation/linux/usage/systemd.md)