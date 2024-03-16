# DrawBot



This project aims to create an CNC based drawing robot that can produce highly precise artworks from digital designs through a combination of hardware and software components.

<br>

### Equipment Required

  - 3D printed the [designs](https://www.thingiverse.com/thing:2349232/files), such as the drawing arm, carriage, etc, using PLA filament (Ultimaker Cura Software).
  - Hardware Required: Arduino UNO, CNC shield, Nema 17 motors, Stepper Drivers - A4988/DRV8825/L298N, Servo Motor - sg90, 12V/1.5A power adaptor, axial rods etc.
  - Software Required: Arduino IDE, GRBL, Universal Gcode Sender Software, Inkscape.

### Operation

  - Open the digital artwork/design in Inkscape
  - Select the “Path” pull down and then “Object to Path”
  - Select the “Extensions” pull down and then “MI GRBL Z Axis Servo Controller”, then “MI GRBL Z Axis Servo Controller"
  - Save the gcode file with appropriate settings
  - Load your file into the Universal G-Code Sender (UGS)
  - Connect the arduino of the DrawBot to the selected port of the computer and press Run

### Challenges
  - Improper model-to-bed adhesion and excess leakage of PLA filament from extruder. Final printed parts were not of proper dimensions and had to be grinded.
  - Motor drivers overheated in short durations.
  - Unavailability of necessary nuts, bolts, screws, and washers.
  - Compatibility issues emerged between different parts due to Version mismatches in various software components

<br>

DrawBot Assembly Manual [Link](https://github.com/ankush2005x/Draw-Bot/blob/main/DrawBotAssemblyUserGuideV3.pdf) 

### Drawbot In Operation Video: [Link](https://drive.google.com/file/d/1lUk22b0WShmfamX5dBkmS7bvJVoDoM_B/view?usp=sharing)




https://github.com/ankush2005x/Draw-Bot/assets/123007735/37ef3e16-8d9c-4160-891d-cad52974a6bd

![Sketch1](https://github.com/ankush2005x/Draw-Bot/assets/123007735/bc7596e4-687c-44f7-8c29-d5aff5ebd220)
![Sketch2](https://github.com/ankush2005x/Draw-Bot/assets/123007735/5bcfc43c-0d02-4763-a03c-ebfa17e2ef8e)
![Sketch3](https://github.com/ankush2005x/Draw-Bot/assets/123007735/657572cc-7cab-4c32-83a9-cdab0c473b9a)



