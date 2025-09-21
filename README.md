# Photocell Light Intensity Meter

This project measures **light intensity** using a photoresistor (LDR) connected to an Arduino Uno.  
The brightness level controls how many of 8 LEDs light up, driven through a 74HC595 shift register.


## 📦 Components Required
- 1 × Elegoo Uno R3 (Arduino-compatible)
- 1 × 830 tie-point breadboard
- 8 × LEDs
- 8 × 220 Ω resistors
- 1 × 1 kΩ resistor (fixed resistor for voltage divider)
- 1 × 74HC595 shift register IC
- 1 × Photoresistor (LDR)
- 16 × Male-to-Male jumper wires


## 🔌 Wiring
### Key Connections
- `lightPin (A0)` → Middle of voltage divider (LDR + 1kΩ resistor)  
- `latchPin (11)` → 74HC595 latch pin  
- `clockPin (9)` → 74HC595 clock pin  
- `dataPin (12)` → 74HC595 data pin  
- 74HC595 outputs → LEDs (with 220 Ω resistors to ground)  
