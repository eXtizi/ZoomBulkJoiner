# ZoomBulkJoiner (Multi-Participant Zoom Meeting Script)
ZoomBulkJoiner is a Python and Selenium-based script that enables users to join a Zoom meeting with multiple instances, using different names. Whether you have a Zoom meeting link or an ID with a passcode, this script allows you to create a virtual army of participants, giving the illusion of a larger attendance. Perfect for pranks, simulations, or any situation where you want to fake participants. Embrace the power of ZoomJoiner and create the ultimate virtual gathering!

- FOR **EDUCATIONAL PURPOSES ONLY** (Please use it at your own risk)

## **Requirements:**

### Python

Have Python3 language installed as the program was written in it.
It can be installed using https://www.python.org/downloads/

- Below are the python libraries used for running the program, you can run either of the code blocks to download all the libraries.
```
pip install selenium, keyboard, questionary, rich
```
```
pip install -r requirements.txt
```

### Chrome

Have Chrome browser installed as the program is based on the chrome drivers.
It can be installed using https://www.google.com/chrome/

## **How It Works**

- The program using the `Selenium` web-driver and Python library for the same, exploits a vulnerability in Zoom's webapp that let's a user join a meeting without needing an account.
- Given the names in the text file, it proceeds to launch an instance of a web-driver and fill the required details to joining the meeting automatically.
- It proceeds to mute audio to prevent an audio loop or unnecessary transfer of microphone audio into the meeting, giving you control over each of the web instances.
- Change names in `names.txt` which will be used in the meeting.
- Example are given in `names.txt`
## whats different ?
- Fixed the Element not locating Problem
- Waiting till webpage Loading Added
- Confirmation Aleart Dissmising

## TO-DO
- Stoping Incoming Video Audio Feed
- Going Headless is Triggers Cloudflare . Gotta Find a Workaround(Maybe a virtual Browser)
- Cookies Accepting Function
  
### Credits:
https://github.com/AverageBlank/ZoomBomber
