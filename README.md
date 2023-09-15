# Bluetooth-FM-Car_Transmitter
This is every step I took to create a Bluetooth FM car transmitter so I could play music in my car. I started from nothing and worked through basic ideas of how it would work, the parts I would need, breadboarding it, and soldering it.

Overview:
Have a PCB that connects the BM20 chip and NS73M chip. Designed that PCB on Eagle.
Then connect M5StickC+ to PCB and program M5 using Arduino code

I will explain briefly what is needed for this project:

List of important things
- NS73M - FM transmitter
- BM20 - Bluetooth chip
- M5StickC+
- Cigarette lighter with USB-C
- PCB for NS73M for breadboard 
      OSH Park NS73M design
- PCB for BM20 for breadboard
      I created a PCB for this using Eagle. Everything for that PCB is in the "eagle" file
- PCB for Bluetooth FM Transmitter
      I created the PCB for this using Eagle. Everything for that PCB is in the "eagle" file
- Arduino code
      Code for the M5StickC+. Everything for that is in the "Arduino code" file
- Capacitor "EEE-FK1A560SR" from Digi-key
- Crystal "R26-32.768-12.5" from Digi-key
- Switch mode DC:DC converter "OKI-78SR-3.3/1.5-W36H-C" from Digi-key
