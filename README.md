# NotSoBasicArduino
 The follwing files are my second foray into Arduino
 
 
## Table of Contents
* [Table of Contents](#TableOfContents)
* [LED_Fade](#LED_Fade)
* [HelloFunctions](#HelloFunctions)
* [NewPing](#NewPing)
---

## LED_Fade
In this assignment you add to your blinking LED, here you are using analog write, delays, and fadeamounts to determine the amount of the fading
### Description & Code
Description goes here
You are going to keep the same wiring as before excpet on the arduino which from the blinking LED ahouls be on pin 13 just move it over to pin 9 and it should fade
(this isn't my code, it belongs to arduino editor)
Here's how you make code look like code:

```C++
  analogWrite(led, brightness);

  // change the brightness for next time through the loop:
  brightness = brightness + fadeAmount;

  // reverse the direction of the fading at the ends of the fade:
  if (brightness <= 0 || brightness >= 255) {
    fadeAmount = -fadeAmount;
  }
```
Talk about how the fade works, here....

### Evidence
[LED Fade on Arduino Create](https://create.arduino.cc/editor/helmstk1/9e044cca-43d7-4d93-885f-e6dec5b4f769/preview)

### Images

### Reflection
 It was a fairly easy task since the code is in https://create.arduino.cc/editor/jlopezc28ccs/078a879a-32c7-46b6-9ce5-c9694d29bf63 but remember if you are using the same wirirng and using the arduino websites code the pinmode on your arduino should be switch from 13 to 9 inorder for the code to work
 (when you visit the arduino website click on examples, which is on the right. then 0.1Basics and scroll down to fade and the code should be there)
 _________
 
 ## HelloFunctions

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

## NewPing

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

