=About=

Boulderino is a fancy breadboard that allows the use of 3-wire (signal, VCC, GND) cables and 2 wire motor cables (A,B) to interface with the Pololu Baby Orangutan, which is usable with the Arduino library. The jacks accept VEX keyed connectors. There is a 4P4C modular jack. 

See [[http://blog.charlesdietrich.com/2012/02/introducing-coloradouino.html|blog post]] for a description of the design process.

==Installation of Programming Environment (Arduino 1.0)==

(Revised 2/19/2012)

# Follow instructions on [[http://www.pololu.com/docs/0J36/3.a|Pololu Windows Drivers and Software]]. Download USB AVR Programmer Windows Drivers and Software (3 MB), not the 173 MB package (does the full package help us in any way?)
# Plug in each of the 3 USB Programmers in turn. Allow the computer to install drivers for each.
# Download [[http://arduino.cc/en/Main/Software|Arduino 1.0 for Windows]]. Unpack the zip file. Put it in the Program Files folder.
# Create two shortcuts to Arduino: one on the desktop and one in the start menu.
# [[http://www.pololu.com/docs/0J17/3|Update the Arduino environment as specified by Pololu]]
# Test by programming the Baby Orangutan with the [[http://www.pololu.com/docs/0J17/4|blink sketch]]. 
 # For Tools > Board, select "Pololu Organgutan or 3pi robot w/ ATMega328p via Programmer"
 # For Tools > Programmer, select "AVR ISP v2"
 # Make sure that the Baby Orangutan behaves properly (i.e. blinks)
# [[http://www.pololu.com/docs/0J17/5|Install the Pololu Arduino libraries]]
# [[http://www.pololu.com/docs/0J17/5.e|Test]] the Orangutan Motor library. Do only OrangutanMotorExample.
 # Connect a two-wire VEX motor to each of the two motor jacks.
 # Test that the trimpot controls the motor speeds.
# Install the Boulderino libraries (TBD)
# Test the Boulderino Libraries with the example (TBD)


