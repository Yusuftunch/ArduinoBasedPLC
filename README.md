# ArduinoBasedPLC

Make your own PLC by using arduino code and Kicad.

## 1. PCB - KiCad
   Since I developed PCB drawings for my company, it would not be right for me to share the entire schematic. However, I will upload details on how to do it or a sample project drawing. For now, I use chips such as Atmega64 and Atmega128 in my PLCs, but I continue to work on STM32. I look forward to those who will support me in this regard.

   
## 2. C# Cutoms IDE / Based on Arduino-CLI
   You can find the codes of the PLC editor I developed for my company at this link. The PLC editor program, which I developed with C# visual studio 2022 IDE, supports C++ code. It performs its operations by calling the arduino-cli program in the background.
[PLC Editor page](https://github.com/Yusuftunch/PLC-EDITOR-ARDUINO-CLI).

More detail please visit [Arduino-cli](https://arduino.github.io/arduino-cli/0.35/)
   
## 3. Library
  I prepared the C++ version of the commonly used PLC software elements for the PLC software of the C++ / Arduino-based microcontroller.
  
  #### I. Timer TON
  
  #### II. Timer TOF
  
  #### III. Timer TP
  
  #### IV. Toogle
  
  #### V. R_trig
  
  #### VI. F_trig
  
  #### VII. Flashor
   
