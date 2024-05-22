# Hardware deisgn balanceboard

Design Goals
  - Four measureable legs
  - USB 3 powered (<950mA)
  - Ultralow RMS Noise ldo (0.8µVRMS)
  - 10v Excitation voltage
  - Precision crystal clock fir filtering (20ppm)
  - Class c3 Loadcells type [LA250-D-100kg](https://allscaleseurope.com/content/uploads/2018/01/LA250-D-single-point-load-cell.pdf)
  - 8 bit decoupled auxiliary pc input
  - 24 bit ADC (ad7124)  

Balanceboard design

<img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/assets/IMG_20240320_190419101_HDR.jpg" width="300"> <img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/assets/IMG_20240320_190425005.jpg" width="300">

LTspice simulation LDO | Boost converters

<img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/assets/lt30xx_ldo.png" width="300"> <img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/assets/lt8330.png" width="300">

Schematic Kicad | 3d-view of bcp

<img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/hw_drawings/schematic.png" width="300"> <img src="https://raw.githubusercontent.com/bcbergmanuu/hw-balance/master/hw_drawings/straingauge.png" width="300">
