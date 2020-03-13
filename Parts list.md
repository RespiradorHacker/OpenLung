# This is a parts list used for reconing and preliminary design work

## Motor

- Range of Nema steppers

## Power

- 18650 lithium cells, or
- Lithium polymer cell
  - Batteries sourced by device builder may not have internal Over voltage protection, Over current protection/short circuit protection, Over temp protection or internal NTC for cell temperature monitoring, and therefore must be fitted to local circuitry.
  - Cell voltage should be monitored and appropriate action taken when cell voltage is too high or low.
- 1S configuration - avoids implementing charge balancing an additonal BMS complications
- Charging circuit to charge at rate of at least 0.5C
- wireless charging module (negates need for power connector and compliance test for said connector)
  - 

## Interface

- Raspberry pi 0, or
- Any micro controller developement paltform in a breakout format
  - at least 16-bit
  - SPI, I2C, UART/USB
  - at least two 10-bit ADC (TBD)
  - 8 GPIO
- External clock
- simple dot matirx display, 16 character by 2 line LCD for example
- rotary encoder with push button detent or
- 4 push button (up, down, left, right or +, - )
- Rep-rap 

## Sensors

- 02 sensor
- air flow / pressure sensor
- humidity & temperature
