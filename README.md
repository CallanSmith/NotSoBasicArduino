# NotSoBasicArduino

The follwing files are my second foray into Arduino

Table of Contents
Table of Contents
LED_Fade
HelloFunctions
NewPing()
LED_Fade
Description & Code
Description goes here

Here's how you make code look like code:

  analogWrite(led, brightness);

  // change the brightness for next time through the loop:
  brightness = brightness + fadeAmount;

  // reverse the direction of the fading at the ends of the fade:
  if (brightness <= 0 || brightness >= 255) {
    fadeAmount = -fadeAmount;
  }
Talk about how the fade works, here....

Evidence
LED Fade on Arduino Create

Images
Reflection
Hello_LCD
Description & Code
Description goes here

Here's how you make code look like code:

Code goes here
Talk about how the code works, here....

Evidence
link goes here

Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

Reflection
