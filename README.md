# RFD900X connector

![conn](setup/conn.png?raw=true "conn RFD900X")

DS-009 standart
https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf

RFD900X
http://rfdesign.com.au/rfd900x-ism-modem/
# RFD900X view

![conn](setup/screen.png?raw=true "View RFD900X")

Where to buy [link](https://store.rfdesign.com.au/rfd-900x-modem/)

# RFD900X setup

To setup RFD900X Firstly you should:
- Download and install [RFD Tool](http://files.rfdesign.com.au/tools/). 
- Download latest firmware [here](https://github.com/RFDesign/rfdesign.github.io/tree/master/Files/firmware). For 17.11.2022 the latest version is [RFDSiK V3.57 rfd900x.bin](https://github.com/RFDesign/rfdesign.github.io/blob/master/Files/firmware/RFDSiK%20V3.57%20rfd900x.bin) and [RFDSiK V3.57 rfd900x2.gbl](https://github.com/RFDesign/rfdesign.github.io/blob/master/Files/firmware/RFDSiK%20V3.57%20rfd900x2.gbl) 
- Open RFD Tool, Click button 'Upload Firmware', select downloaded .bin or .gbl
- Reconnect
- Set all parameters


All parameters should be set relative to next lines:

- Version should be: RFD SiK 3.57 on RFD900X
- Format: 63
- Boud: 57
- Air Speed: 64
- Net ID: 25
- Tx Power: 30
- Mavlink: ON

- Min Freq: 902000
- Max Freq: 928000
- N of Channels: 50
- Duty Cycle: 100
- LBT Rssi: 0
- Max Window: 120
- AES Encryption: 128b
- AES KEY: 603DEB1015CA71BE2B73AEF0857D7781

- In base station case: GPO1_1SBUSIN Checked 
- On board case: GPO1_1SBUSOUT: SBUS1_NOFAIL

As the final result parameters should looks like this

![setup](setup/setup.png?raw=true "setup RFD900X")


- Datasheet on [RFD900X](http://files.rfdesign.com.au/Files/documents/RFD900x%20DataSheet%20V1.1.pdf)

- User manual presented [here](http://files.rfdesign.com.au/Files/documents/RFD900x%20Peer-to-peer%20V3.X%20User%20Manual%20V1.2.pdf)
