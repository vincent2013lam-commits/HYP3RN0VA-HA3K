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





