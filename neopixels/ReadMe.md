# Backstory
I am working on a long term project which tries to create the ultimate vibe in a dorm room. This was one of the first projects and NO! I'm not happy about just using a strip of lights but I treat it as a "base coat of paint" for the room.
This is just a basic strip of 200 neopixels that alternates colors. Here's what I mean:
#### ex 1:
"Set the color to red", "Set the color to green" \n 
rgrgrgrg...

#### ex 2:
"Set the Color to red" 

r0r0r0r0...

"Set the Color to blue"

rbrbrbrb...

#### ex 3:
"Set the Color to red"

r0r0r0r0...

"Set the Color to blue"

rbrbrbrb...

"Set the Color to green"

gbgbgbgb...

"Turn the pixels off"

00000000...

# Setup
I'm using an ESP-01 to control the pixels through a Arduino IoT Cloud. I have 5v going to the pixels and a 5v-3.3v
buck converter which powers the chip which sends data to the pixels.

![Pixel Voltage going into both the pixels and a voltage converter. The converter powers the controller which sends data to the pixels.](https://github.com/gdegidy/coolRoom/blob/main/Images/GithubImages/BetterVoltageSetup.png)