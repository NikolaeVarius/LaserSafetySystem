#Laser Safety System
A low cost laser cutter/engraver safety monitoring system for K40 and similair laser systems.

##Features

####Door interlock event
Door interlock input for the main work area door.
***
####Temperature monitoring event
Input for monitoring coolant temperature.
***
####Coolant flow monitoring event
Input to monitor coolant flow using low cost flow sensor.
***
####Audible Alarm
Critical event sets off buzzer with continuous tone.
***

####Automatic Laser Shutdown
Critical event disables the Laser
***
##Arduino Pin Assignments
####These pin assignments are based on the Arduino Nano board
  
  1. D2 - Flow sensor input
  2. D3 - Door microswitch input
  3. D4 - Buzzer alarm output
  4. D5 - Relay trigger pin to disable laser
  5. A0 - Coolant temperature sensor input

***
####Required Hardware

The links are just examples of the required items, you may be able to get them cheaper on web sites other than ebay.

  1. Arduino Nano http://www.ebay.ca/itm/USB-Nano-V3-0-ATmega328-CH340G-5V-16M-Micro-controller-board-For-Arduino-/381523742462?hash=item58d4964efe:g:5pwAAOSwy4hUTv2u
  2. Microswitch for door interlock http://www.ebay.ca/itm/1-Pcs-Micro-Switch-Spdt-Hinge-Roller-Lever-15A-V-156-1C25-/181985068688?hash=item2a5f27c690:g:xYAAAOSw5dNWj3eU
  3. TMP36 temperature sensor for coolant temperature monitoringhttp://www.ebay.ca/itm/2pcs-TMP36GT9Z-TMP36GT9-ORIGINAL-Low-Voltage-Temperature-Sensors-NEW-/171906967235?hash=item28067426c3
  4. 5V relay to disable laser firing http://www.ebay.ca/itm/Effective-Stable-1-Channel-5V-Indicator-Light-LED-Relay-Module-For-Arduino-SCW-/231718093803?hash=item35f37983eb:g:okkAAOSwT5tWGzNb
  5. I2C 2004 LCD display http://www.ebay.ca/itm/New-Yellow-Serial-IIC-I2C-TWI-2004-20X4-Character-LCD-Module-Display-For-Arduino-/131551735668?hash=item1ea1182f74:g:OjMAAOxyUrZS0ARf
  6. Flow sensor http://www.ebay.ca/itm/New-1-2-Water-Flow-Switch-Hall-Flow-Meter-Control-1-30L-min-Black-1pcs-/291411734936?hash=item43d97e3198:g:KAcAAOSwBLlVC6K3

***

##Arduino Libraries

Please use the arduino libraries in the libraries folder, as they are slightly modified from the original ones. You will get compile errors if you do no use these ibraries

***

##Schematic

Coming soon, however it should be pretty onvious how to connect it all up. :)

***
