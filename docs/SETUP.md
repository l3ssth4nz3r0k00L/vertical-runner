### Display Setup — Vertical Runner

#### Official Waveshare Instructions
Follow the Waveshare guide for the 3.5" Resistive Touch LCD here:  
 [Waveshare Wiki — 3.5" LCD](https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(B)_Manual_Configuration))  
*(make sure you’re matching your exact panel + driver version)*
---
#### Vertical Runner Clarification
After running through Waveshare’s setup script, the display may boot in the wrong orientation.  
The missing step is to run this terminal command:

```bash
sudo ./LCD35B-show-V2 270
