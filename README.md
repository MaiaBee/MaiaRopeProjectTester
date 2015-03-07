# MaiaRopeProjectTester
Test rope controll on soundstorm 
Attached is the sensor code.  (PLEASE NOTE:  I do not know which sensors map with which motors, so I'd recommend running this and manually brushing a magnet up against each sensor so you can make note of which one goes with which. Do let me know what you find.  Additionally, Motors may not move in the direction specified below.  I didn't get to confirm direction, so please jot this down and send my way also)

Instructions for use:

 - Load this onto the Arduino.
 - With the Arduino hooked to the computer, open up the Serial window. (its the last icon on the right of the dark blue bar in Arduino)
 - Set Baud Rate to 9600
 - The 12V power supply should NOT be connected to the Arduino, but directly to the separate power connection (the red/black wires going to a barrel connection)
 - Once connected by USB, with external supply plugged into shield board, and with external power supplies for motors on, you can open serial window and send commands.

 - Commands are (type a single letter and hit enter/press send): 

a - Motor 1 Move Left (1 Sec)
s - Motor 1 Move Right (1 Sec)

d - Motor 2 Move Left (1 Sec)
f - Motor 2 Move Right (1 Sec)

g - Motor 3 Move Left (1 Sec)
h - Motor 3 Move Right (1 Sec)

If the sensor detects the magnets, it should send you a message over Serial. However, if you want to check yourself, you can send the following letter for each sensor.  You'll get a 1 for one, 0 for off.

j - Sensor 1
k - Sensor 2
l - Sensor 3
