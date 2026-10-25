# RGB MIDI Keypad 
A 25 key capacitive touch MIDI keypad PCB with :
- Seeed Studio XIAO RP2040 : To process everything 
- MPR121 capacitive touch sensors : to connect the 25 keys (the rp2040 doest not have enough gpio pins for 25 keys so this is needed)
- capacitive keys - no physical keys , just touch the copper pads to make music
- RGB LEDs - LED under each key which lights up when you touch a copper pad
- Octave Control Switch - Click the 2 mechanical keys to switch between up and down octaves
- Rotary Encoder - to control the volume and much more (tbh its there cause its fun to twist this and act like a DJ)
- Slide Potentiometers - to control filters , effects and anything u want
- A display - to display the settings and cool animations
- A power ON LED and a LED which blinks with you press any key except the copper pads
### HERE IS THE IMAGE OF THE PCB 
<img width="646" height="567" alt="image" src="https://github.com/user-attachments/assets/a0aa0ff2-8cec-4767-a94b-2a5f65dd928e" />
<img width="587" height="519" alt="image" src="https://github.com/user-attachments/assets/872c73b0-a43b-4677-bf0a-a969b7a0c57f" />
<img width="813" height="547" alt="image" src="https://github.com/user-attachments/assets/e778bbda-52f9-469a-9e63-7270643a7bb0" />

## BOM:
| Components | Qty | Unit Price | Total Price | Link |
| -------- | -------- | -------- |  -------- | -------- | 
| Seeed Studio XIAO RP2040 | 1 | $5.59 | $5.59 | [supplier](https://robu.in/product/seeed-studio-xiao-rp2040-v1-0/) | 
| MPR121 Capacitive Touch Modules | 3 | $1.15 | $3.45 | [supplier](https://robu.in/product/mpr121-breakout-v12-capacitive-touch-sensor-controller-module-i2c-keyboard/)
| 0.91 inch 128x32 Blue OLED Display | 1 | $2.23 | $2.23 | [supplier](https://robu.in/product/0-91-inch-128x32-i2c-iic-serial-blue-oled-lcd-display-module/)
| Rotary encoder Dev board | 1 | $1.04 | $1.04| [link](https://robu.in/product/EC11%20Rotary%20Encoder%20Module%20with%20Knob%20Cap%20for%20Development%20Boards/) |
| WS2812B LED | 25 | $0.08 | $2.00 | [link](https://robu.in/product/sme-ws2812b-2020-addressable-rgb-pixel-led-worldsemi/) |
| Power Indicator LED | 2 | $0.011  | $0.8 | [link](https://robu.in/product/3mm-green-dip-led-pack-of-50/) | 
| PTA2043 Slide Potentiometer | 2 | $2.61 | $5.27 | [link](https://robu.in/product/pta2043-2010cib254-bourns/) | 
| SW_Cherry_MX switch | 2 | $0.5 | $1 | [link](https://www.sunrom.com/p/cherry-mx-blue-switch-mx1a-e1nn) | 
| PCB | 1 | $10 | $10 | [link](https://robu.in/product/online-pcb-manufacturing-service/) |
| Total:||$30 |
