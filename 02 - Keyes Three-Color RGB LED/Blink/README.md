# Blink
Repeatedly blinks each color (red, green, blue) in succession

## Parts Used
* 1x [Keyes Three-Color LED](http://www.amazon.com/DIY-3-Color-RGB-Module-Arduino/dp/B0100A92BC)
* 1x [Ardunio UNO R3 Board Module](http://www.amazon.com/Arduino-Board-Module-ATmega328P-Blue/dp/B01A0MONA0)
* 1x [Breadboard] (http://www.amazon.com/Veewon-SYB-170-Color-Breadboard-Circuit/dp/B00OP4FQVU)
* 6x [Male-to-Male Jumper Wires](http://www.amazon.com/Phantom-YoYo-Dupont-Cable-10cm/dp/B00KOL8O6C)
* 3x [330 Ohm Resistors](http://www.amazon.com/E-Projects-100EP514330R-330-Resistors-Pack/dp/B0185FGN98)
* 1x [USB 2.0 Cable A-Male-to-B-Male](http://www.amazon.com/AmazonBasics-USB-2-0-Cable--Male/dp/B00NH11KIK)

## The Wiring
![Wiring Example 1](wiring-01.JPG)
![Wiring Example 2](wiring-02.JPG)
![Wiring Example 3](wiring-03.JPG)

(Note: The red and green pins in my sensor seem to be backwards. While red looks like it's connected to pin 9, writing to pin 9 turns the LED green. Similarly, green is wired to 10, but writing to it turns the LED red. This is handled in the code.)

## The Code
See [blink.ino](blink.ino)
