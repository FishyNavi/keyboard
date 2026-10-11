# Hackyboard!
## PCB
`pcb/`
The PCB was designed in KiCAD 10.
![](image-1.png)
![](image-2.png)
- The PCB is designed for Cherry MX magnetic switches. 
- The sensors' measurement range is ~82.5mT.
- The MCU that's used is STM32G431CBT6

## FIRMWARE
./firmware
The firmware is based on [libhmk](https://github.com/peppapighs/libhmk)
by peppapighs, which is licensed under GPL-3.0. Changes and additions in
`firmware/` (including the MCU support) are therefore also
released under GPL-3.0, see `firmware/LICENSE`.
*For now it just is. I didn't test it yet*


