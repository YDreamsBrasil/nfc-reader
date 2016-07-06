# About 
Python script that can receive and send UDP messages containing card IDs
from the ACR122U NFC reader. Read the script to change configs.

### References

*pyscard*
(Sending APDUs to a Smart Card Obtained from Card Monitoring)
http://pyscard.sourceforge.net/user-guide.html#the-reader-centric-approach

### Running
`Run pip install -r requirements.txt`
`python nfc-server.py`

#### Socketserver doc
https://docs.python.org/2/library/socketserver.html

#### Drivers for the reader
http://www.acs.com.hk/en/driver/3/acr122u-usb-nfc-reader/

#### PDF with hex commands
http://downloads.acs.com.hk/drivers/en/API-ACR122U-2.02.pdf
