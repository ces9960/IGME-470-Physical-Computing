#Digital IO

##Image
I disassembled the project already, so the image is an MS Paint mockup of how the inputs and outputs were set up.
https://github.com/ces9960/IGME-470-Physical-Computing/blob/main/Digital-io-mockup.png

##Code
https://create.arduino.cc/editor/ces9960/f2f3e464-317d-43ef-8f7f-decd6388ed1b

##Description
I used 2 digital inputs (button and capacitive touch), 2 LEDs, and the built-in LED on the Arduino.  Holding the button caused the 3 LEDs (2 external, 1 built-in) to blink in a loop where only one LED was on at a time.  Due to the way it's coded, releasing the button doesn't stop the LEDs from blinking until the current loop cycle is over.  Touching the capacitive touch sensor turns on all of the LEDs if the button is not pressed.  I mostly just wanted to expand on the basic blinking LEDs, including making several LEDs blink in sequence, and using both the built-in LED and external LEDs.
