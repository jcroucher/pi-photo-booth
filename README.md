# pi-photo-booth
Automatically exported from code.google.com/p/pi-photo-booth

Raspberry Pi Photo Booth software written in Python.

This photo booth software runs a random slideshow of all photos taken. When a user presses the button connected to the Raspberry Pi GPIO pin ( Default 18 ), it initiates a photo taking sequence



1. Switches the camera to preview mode so users can see themselves and allow for auto focus 

2. Starts a countdown until the photo is taken 

3. This process is run 4 times to take 4 different photos of the user 

4. The 4 photos are then resized and combined onto a 4x6" photo. This photo has space for a watermark. Replace blank.jpg with your default image to easily customise the watermark for different events. 

5. If enabled, the photo is then sent to the default printer installed on the Raspberry Pi 

6. Preview of the combined image is displayed to the user 

7. After a timeout the system switches back to a random slideshow



Keys

- Escape - Close application 

- F - Toggle between Full Screen and Windowed Mode.

Hardware Used 

- Raspberry Pi B+ 

- Raspberry Pi Camera 

- 7" LCD with HDMI 

- Push Button 

- A4 Photo Frame ( Box Style )

Video of my prototype - https://www.youtube.com/watch?v=BvRVFNYOtuU

Sample Printout: http://i.imgur.com/OrlO5hd.jpg?1
