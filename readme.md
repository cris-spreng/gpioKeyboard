# Adafruit Custom GPIO Keyboard

This is an adaptation of the code provided by Adafruit for building a gamepad with Cherry MX Switches, in this case we needed to have 15 buttons so the code has been modified to create a new different HID package each time keys are pressed sice we can only transport 6 keycodes each time.

It's a very simple solution but it get's the job done.

The original code can be found at:
https://cdn-learn.adafruit.com/assets/assets/000/038/101/original/gpioKeyboard.zip
