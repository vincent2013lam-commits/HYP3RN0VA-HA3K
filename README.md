Heyo! PR0J3CT: #H9P3RN0VA is a musical keyboard where you can create your own custom musical tracks. H9P3RN0VA will be a PCB design, first the design process will be on a schematic editor, then transferred to the PCB editor where the music magic happens.

To make a MIDI KEYBOARD like H9P3RN0VA, open the schematic editor on Kicad and add the following components below:
- Waveshare Microcontroller: Brain of the system
- Conn 01x09 Capacitive Touch Keys: Literally the keys you play on your keyboard
- SW_PUSH Low-Profile Switches: Functions the sound when a key is pressed
- Rotary Encoder: Ensures the sound is smooth
- Bourns Slide Potentiometer: Controls the volume
- SK6812MINI-E Neopixels: Controls the lighting of the instrument

<img width="434" height="481" alt="Screenshot 2026-10-21 180846" src="https://github.com/user-attachments/assets/db2d0b89-9d06-4fdd-8ad2-0c6bf72fd6d2" />

After making the scenes, we move on to assigning the footprints, the base layer to the function of our musical keyboard

<img width="756" height="259" alt="Screenshot 2026-10-22 212024" src="https://github.com/user-attachments/assets/b84f279d-927f-4573-bf21-f13498cb9719" />

We'll transfer our schematic into the PCB editor, it should look something like this:

<img width="301" height="243" alt="Screenshot 2026-10-22 214227" src="https://github.com/user-attachments/assets/bc011bbc-ed1a-44ff-9996-b4a087928304" />

After the inital design, we're customizing the capacitive keys footprint, transfering them to assign on the schematic, and placing them into the PCB editor:

<img width="571" height="298" alt="Screenshot 2026-10-23 170059" src="https://github.com/user-attachments/assets/839163cb-8f01-4a31-975f-662454df2b18" />

<img width="375" height="437" alt="Screenshot 2026-10-23 170030"
src="https://github.com/user-attachments/assets/1392667a-dbfa-4e67-ad18-ca7c96fb587e" />

Then, comes the wiring, edging, and rounding the corners with the Edge.cuts, F.cu, B.cu, F.silkscreen and B.silkscreen:

<img width="703" height="427" alt="Screenshot 2026-10-23 215427" src="https://github.com/user-attachments/assets/19eec4d1-d2de-43ec-b045-33adb1ae1077" />

<img width="528" height="427" alt="Screenshot 2026-10-23 215444" src="https://github.com/user-attachments/assets/cb9c6d10-a410-45d1-b108-d8305d4493e5" />

<img width="531" height="447" alt="Screenshot 2026-10-24 212755" src="https://github.com/user-attachments/assets/f3106f06-1c36-4ee3-afb7-6f1259723bf2" />

<img width="549" height="424" alt="Screenshot 2026-10-24 212937" src="https://github.com/user-attachments/assets/f98903d2-89da-4aa9-8f12-0b42c9c09e89" />

<img width="664" height="507" alt="Screenshot 2026-10-25 102440" src="https://github.com/user-attachments/assets/afc20e7d-3aee-41ad-96b8-ed2e1355c7db" />

The 3D modeling's next, cuz what's a keyboard without 3D stuff to press and play on???

<img width="590" height="453" alt="Screenshot 2026-10-25 171433" src="https://github.com/user-attachments/assets/ec4490ec-bc9d-46e1-a678-24f35220ce34" />

After is the fabrication, which after installing and going onto a PCB website, it will turn out like this:

<img width="748" height="174" alt="Screenshot 2026-10-25 172935" src="https://github.com/user-attachments/assets/f9903657-2992-4275-b251-9e69976e8fa4" />









