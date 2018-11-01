# Tritech hackoween hackathon

#### WiFi
SSID: 3TGuest

Pass: SkrivStora3SS


This repository contains two files, `utils.py` containing a few necessary api:s and `solve.py` which is the starting point for the challenge.

## Getting started
To get started you need to download this repository and have python3 installed on your machine. This challenge also requires you to have pyserial and requests installed. By using the api:s from `utils.py`, your current score will be published on the screen during the event provided that you have an internet connection.


### Installing python3, pip3, pyserial and requests
If you don't already have python3 and pip3 installed you need to install it. 



### Windows
To to install python3 on Windows go to: <https://www.python.org/> and download python 3.X.X under the `Download` tab.
This will automatically install pip3.

Make sure to check the following boxes:
![](/images/windows_python_setup.png)

Install pyserial and requests:
``` bash
pip3 install pyserial
pip3 install requests
```


### Linux
``` bash
# Or similar depending on your systems package manager
sudo apt-get install python3
sudo apt-get install python3-pip

pip3 install pyserial
pip3 install requests
```


### macOS
``` bash
# If you don't have brew installed, install it by running:
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# Installing python3 will automatically install pip3
brew install python3

pip3 install pyserial
pip3 install requests
```


### Find the correct serial port
Next, connect your device (Arduino) and determine the name of the connected serial device. Edit the `solve.py` script accordingly (e.g. "COM15" for Windows, "/dev/ttyACM0" for Linux, /dev/tty.usbserial-A9UTPFVR)

For Linux and macOS:
``` bash
ls -l /dev/tty*

# On Linux the port name likely contains "ACM"
# On macOS the port name likely contains usbserial-

```

For Windows
````bash
# Method 1: Go to "Device manager > Ports (COM & LPT)"
# Method 2: Type "mode" in the command promt
```

You should be set! Now hack away! 