# Studs 2018 Tritech hackathon
This repository contains two files, `utils.py` containing a few necessary api:s and `solve.py` which is a good starting point for the challenge.

## Getting started
To get started you need to clone this repository and have python3 installed on your machine. This challenge also requires you to have pyserial and requests installed. By using the api:s from `utils.py`, your current score will be published on the screen during the event provided that you have an internet connection.

To install pyserial and requests run:
``` bash
# If you dont have pip installed you can run (or similar):
sudo apt-get install python3-pip
pip3 install pyserial
pip3 install requests

```

Next, connect your device and determine the name of the connected serial device. Edit the `solve.py` script accordingly (e.g. "COM15" for windows or "/dev/ttyUSB0" for Linux)

Hack away! 