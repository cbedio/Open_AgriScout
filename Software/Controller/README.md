# Flashing Controller Software to the OpenScout Robot

## Install time = 5 minutes

The main script that needs to be uploaded to the Arduino board is located within the `Software` folder of this directory. To upload the sketch we recommend that you use the Arduino IDE, which can be obtained from [arduino.cc](https://www.arduino.cc/en/software).

## Getting started

1. Open the Arduino IDE and load in the `refined_pid.ino` file (`File -> Open -> select_file`).
1. Upload the sketch (see settings below)

### Settings

The firmware can be uploaded through `Sketch -> Upload` or by pressing the upload button.

Connect the Arduino board to the computer and set the port it is attached to:
  
- `Tools -> Board -> Arduino AVR Boards -> *Select the Arduino Board*`
- `Tools -> Processor -> *Select the Arduino Prosessor*`
- `Tools -> Port -> *Select the USB port*`


## Attribution

Github history lost due to moving files.


README.md updated by https://github.com/Rudi-Cato

Twist_via_MQTT.ino created by https://github.com/Rudi-Cato

refined_pid.ino created by https://github.com/Tobies-Cormac
