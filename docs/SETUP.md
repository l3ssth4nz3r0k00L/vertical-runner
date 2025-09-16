### Display Setup — Vertical Runner

### NOTE: I could NOT get this to work correctly with Kali Linux or Parrot OS. I only got this to fully function on Raspbian.  Further testing I would think could yield different results, maybe on a rpi5 and different Waveshare LCD class display?

#### Official Waveshare Instructions
Follow the Waveshare guide for the 3.5" Resistive Touch LCD here:  
 [Waveshare Wiki — 3.5" LCD-B](https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)_Manual_Configuration))  
*(make sure you’re matching your exact panel + driver version)*
---
#### Vertical Runner Clarification
After running through Waveshare’s setup script, the display may boot in the wrong orientation.  
The missing step is to run this terminal command:

```bash
sudo ./LCD35B-show-V2 270
