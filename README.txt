Hi!

This is my experiment with getting a Gigabit PHY to send UDP packets. It was 
tested on the Digilent Nexys Video development board.

The first four switches select the speed that packets are sent - between 1 per second
("0000") to full speed ("1111").

Currently it only transmits at 1Gb/s, and although the PHY is set to auto-negotiate to 
the fastest speed I have have had to set the receiving port to 1Gb / full duplex to 
make it work.

Hopefully it will be of use to somebody....