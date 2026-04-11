# Analog Light Intensity Meter

I wanted to make some projects without microcontroller so I made this **light intensity meter** which indicates light in 10 distinct levels.
![3D Model](Analog%20Light%20Intensity%20Meter/Images/3D.PNG)

## Working

The **LM324N IC** contains 4 OpAmps which are being used as Comparaters. They compare two voltages i.e. **reference voltage** and **signal voltage** and  if signal voltage is higher than reference voltage the output is on and all the LEDs till that level turn on.

## PCB and Connections

The Project is powered by a 9V source the thee +9V goes to the VCC of op Amps and top of the voltage divider bridge and top of the sensitivity control area the Gnd goes to the GND of op Amps and bottom of the voltage divider bridge and bottom of the sensitivity control area . The signal from the senstivity control area goes to the +ve of op amps and the 10 voltage levels are connected to -ve of 10 individual op Amps.
|Schematics|Tracks|
| :---: | :---: |
| ![schemetics](Analog%20Light%20Intensity%20Meter/Images/Schematics.PNG) | ![Tracks](Analog%20Light%20Intensity%20Meter/Images/Tracks.PNG) |

## Bill of Materials (BOM)

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| LEDs | Indicator | 10 | 7 | [LED](https://www.aliexpress.com/item/1005003337390606.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%206.68%21USD%206.68%21%21USD%206.68%21%21%21%402141131717759137152123058eb796%2112000025287186811%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| PCB | to assemble the project | 1 | 35 | [PCB](https://cart.jlcpcb.com/quote/gerberviewThree/?qs=edae4f3f128a488bbbc25f9c6c296d6c_1_0_1_0_0.html) | AliExpress
| IC Base | to solder ICs on PCB or Veroboard |  | 2 | [IC Base](https://www.aliexpress.com/item/32866483409.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%202.53%21USD%202.53%21%21USD%202.50%21%21%21%402141131717759137152123058eb796%2165442005257%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| Potentiometer | Control Senstivity | 1 | 3 | [Potentiometer](https://www.aliexpress.com/item/1005007730415902.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%205.09%21USD%203.91%21%21USD%203.87%21%21%21%402141131717759137152123058eb796%2112000042014621765%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| LDR | Detecting Light level | 1 | 3 | [LDR](https://www.aliexpress.com/item/1005010362917938.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%206.96%21USD%203.34%21%21USD%203.31%21%21%21%402141131717759137152123058eb796%2112000052228563358%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| 1kΩ Resistor | For Voltage Divider Bridge | 11 | 2 | [1K Resistor](https://www.aliexpress.com/item/1005009177180559.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%202.16%21USD%202.16%21%21USD%202.09%21%21%21%402141131717759137152123058eb796%2112000048205104387%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| 470Ω Resistor | for LEDs | 10 | 2 | [470R Resistor](https://www.aliexpress.com/item/1005009177180559.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%202.16%21USD%202.16%21%21USD%202.10%21%21%21%402141131717759137152123058eb796%2112000048205104379%21ct%21PK%212961473668%21%211%210%21) | AliExpress |
| LM324N | Quad OpAmp ICs | 6 | 7 | [LM324N IC](https://www.aliexpress.com/item/1005008583669771.html?spm=a2g0o.cart.0.0.12d438daRTPLv9&mp=1&pdp_npi=6%40dis%21USD%21USD%202.28%21USD%202.28%21%21USD%202.17%21%21%21%402141131717759137152123058eb796%2112000045869429620%21ct%21PK%212961473668%21%211%210%21&pdp_ext_f=%7B%22cart2PdpParams%22%3A%7B%22pdpBusinessMode%22%3A%22retail%22%7D%7D) | AliExpress |