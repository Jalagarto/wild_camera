# wild_camera
attempt to put all packages together to run the camera in the wild (raspberry pi)

### Project description:
1. Hardware:
    1. Find out if we need IR leds for the raspberry NoIR camera
    2. Battery --> a mobile phone external battery should make it.

2. Software:
    1. Movement detection
    2. Camera module to capture images when necessary:
    3. Logic: 
        1. get images every second.
        2. if there is movement record the image and keep recording every second  
           for the next 10 secs.

_____

**Try pictures first, then video:**  

Advantages: easier prototyping, less power consumption
