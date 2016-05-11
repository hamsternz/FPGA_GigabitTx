Hi!

This is my experiment with getting a Gigabit PHY to send UDP packets. It was 
tested on the Digilent Nexys Video development board.

The first four switches select the speed that packets are sent - between 1 per second
("0000") to full speed ("1111").

The next two switches (4&5) controls the TX speed.
00 => Idle - does not transmit data
01 => 10BaseT
10 => 100BaseT
11 => 1000BaseT

Although the PHY is set to auto-negotiate this design does not yet autodetect the 
link speed. You will need to set the receiving port to the matching speed &full duplex 
to make it work.

Hopefully it will be of use to somebody....