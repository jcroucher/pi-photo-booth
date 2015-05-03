**Raspberry Pi Photo Booth software written in Python.**

Direct link to the code https://code.google.com/p/pi-photo-booth/source/browse/photobooth.py

This photo booth software runs a random slideshow of all photos taken.
When a user presses the button connected to the Raspberry Pi GPIO pin ( Default 18 ), it initiates a photo taking sequence

<br />1. Switches the camera to preview mode so users can see themselves and allow for auto focus
<br />2. Starts a countdown until the photo is taken
<br />3. This process is run 4 times to take 4 different photos of the user
<br />4. The 4 photos are then resized and combined onto a 4x6" photo. This photo has space for a watermark. Replace blank.jpg with your default image to easily customise the watermark for different events.
<br />5. If enabled, the photo is then sent to the default printer installed on the Raspberry Pi
<br />6. Preview of the combined image is displayed to the user
<br />7. After a timeout the system switches back to a random slideshow

<br />**Keys**

- Escape - Close application
<br />- F - Toggle between Full Screen and Windowed Mode.

**Hardware Used**
<br />- Raspberry Pi B+
<br />- Raspberry Pi Camera
<br />- 7" LCD with HDMI
<br />- Push Button
<br />- A4 Photo Frame ( Box Style )

Video of my prototype - https://www.youtube.com/watch?v=BvRVFNYOtuU

<br />Sample Printout
<br />http://i.imgur.com/OrlO5hd.jpg?1