# RFD900X connector

![conn](setup/conn.png?raw=true "conn RFD900X")

DS-009 standart
https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf

# RFD900X view

![conn](setup/screen.png?raw=true "View RFD900X")

# RFD900X setup

![setup](setup/setup.png?raw=true "setup RFD900X")

default boudrate 57600

AES KEY: 603DEB1015CA71BE2B73AEF085700000

## You can just update params by AT mode:
```
+++
ATI5
S8:MIN_FREQ=902000
AT&E?
603DEB1015CA71BE2B73AEF085700000
```
