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
    4. Final touch: 
        1. Save battery:
            1. Send to sleep for a while when nothing happens.
            2. Disconnect usb, hdmi, WiFi, Bluetooth when necessary
        2. Use VNC to manage from my mobile... Create an easy connection app or just make it easy to handle it from VNC mobile when connected to the same wifi.  
        I.e., connect. Check that the program is running, see a picture, disconnect WiFi to save power
_____

**Try pictures first, then video:**  

Advantages: easier prototyping, less power consumption
