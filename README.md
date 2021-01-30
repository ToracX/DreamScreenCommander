# Overview

Python script that allows you to control your DreamScreen Ambient TV device with python.
While this can be used in many ways where you can have your computer call the script upon events and programatically enter the option values.

You can hard code the IP so that you dont have to use the -i option everytime. 
Uncomment the following 2 lines in the script:
#IP = "192.168.1.2"
#endpoint = (IP, 8888)


## How to use the script:

#### Example: "python dreamscreen.py -i 192.168.1.2 -m 0"


Showing help screen -h
Setting IP address: -i <ip address>


- Changing Modes: -m <number>
- Changing Brightness: -b <number>
- Changing Sources: -s <number>
- Changing Scenes: -a <number>
- Changing color: -c <0-255 0-255 0-255>
  


## Ideas for usage
* Automatically adjust Dreamscreen brightness based on room ambient brightness
* Control your Dreamscreen inputs with a Harmony remote control - no phone needed!
* Use Dreamscreen as a light with with your smart home instance and a raspberry pi
* Do Voice UI (Alexa-styled) control of the Dreamscreen (Windows Speech Marcos, Jasper)
