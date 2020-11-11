# JetBot Log

## Problems

* Display went to sleep fast. It was fixed after shutting down and removing the htmi cable and powering up again.
* Barrel Jack power up didn't work.

## Features

* OLED - https://www.jetsonhacks.com/2019/12/03/adafruit-pioled-on-jetson-nano/
* I2C - `sudo i2cdetect -y -r 1`

## Important

* After jetbot docker was enabled, the GUI got diabled. Even though login pw was diabled, the boot got stopped at tty login.