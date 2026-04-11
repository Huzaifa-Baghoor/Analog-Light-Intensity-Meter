# Analog Light Intensity Meter

I wanted to make some projects without microcontroller so I made this **light intensity meter** which indicates light in 10 distinct levels.

## Working

The **LM324N IC** contains 4 OpAmps which are being used as Comparaters. They compare two voltages i.e. **reference voltage** and **signal voltage** and  if signal voltage is higher than reference voltage the output is on and all the LEDs till that level turn on.