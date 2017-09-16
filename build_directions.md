Line Follow Build Directions!
============================

> **Parts List:**
> - Dual Gearmotor (3-6V power)
> - Motor Driver https://www.pololu.com/product/2130
> - 40mm Wheel Pair
> - .5" Ball Caster (size may change)
> - Teensy LC (3.3V) https://www.pjrc.com/teensy/teensyLC.html
> - 4 AA holder (6V output max -> 4V) w/ switch
> - 48 pack of AA (need 4)
> - Breadboard 
> - Micro USB Cable
> - IR Sensor https://www.pololu.com/product/2456

Steps
------

We encourage you to read through all the steps before you start. It's a good idea to test the sensors and motors separately before putting them together!
- Construct gearbox (instructions on box)
- Attach wheels and battery holder to gearbox
- You can program in the teensy using the Arduino IDE. (Install here: https://www.arduino.cc/en/Main/Software)
- You will also need to download software to interface arduino and teensy. (Download here: https://www.pjrc.com/teensy/td_download.html)
- Electrical components (should test separately on breadboard before attaching to robot):
    - Sensors to teensy (sensors run on 5V so will need to add voltage divider to signal lines since teensy inputs are 3.3V).
    - Motor driver to teensy and motor
    - Battery power supply to rails 
    - Sensor has 5v output - use voltage divider (resistors) to drop this to 3.3v for the teensy
    - Circuit schematic below
- Mount sensors
- Solder connections from motor driver to motor (there are two small metal contacts on each motor - see schematic)
- Upload code onto teensy (there is code in the github repo but we used different sensors! use this code as a reference only- it will not work with your bot.)
- Ask our members if you have any questions!
- Have fun!