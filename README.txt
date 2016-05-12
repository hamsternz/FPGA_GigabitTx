Hi!

This is my experiment with getting a Gigabit PHY to send UDP packets. It was 
tested on the Digilent Nexys Video development board.

The first four switches select the speed that packets are sent - between 1 per second
("0000") to full speed ("1111").

The LEDs show the link state/speed:

LED 0 => 10BaseT
LED 1 => 100BaseT
LED 2 => 1000BaseT
LED 3 => Full Duplex.

Hopefully it will be of use to somebody....