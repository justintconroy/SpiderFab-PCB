# SpiderFab Control Board

This board is made to control [SpiderFab](https://github.com/justintconroy/SpiderFab).

It's mostly just my attempts to learn how to make PCBs using EAGLE.
Version 1.0 supports:
* 2.3-16V battery power supply
* 1000mAh charger for internal LiPo battery
* Charge via USB or 5mm barrel connector
* 12 servos
* 2 DC motors

# Next version
I'm already thinking of what I might change on this to make it more
generally useful. Potential changes:
* Add a [GPIO expander](https://www.mouser.com/ProductDetail/NXP-Semiconductors/PCA9685PW118?qs=sGAEpiMZZMvKM5ialpXrmnWDpPMxsdrM)
  to support more actuators.
* Switch to an SMT version of the motor driver to make some more space
  on the board. (might be a bad idea if we want to make it easy to
  replace burned out drivers by socketing them).
* Add another motor driver to allow controlling 4 motors.
