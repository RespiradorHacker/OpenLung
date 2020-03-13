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
  - Example: [https://www.ebay.co.uk/i/264394772583?chn=ps&var=564016992535&norover=1&mkevt=1&mkrid=710-134428-41853-0&mkcid=2&itemid=564016992535_264394772583&targetid=876487124366&device=c&mktype=pla&googleloc=1007266&campaignid=9441121590&mkgroupid=95891581676&rlsatarget=aud-381667280803:pla-876487124366&abcId=1140496&merchantid=138346494&gclid=Cj0KCQjw3qzzBRDnARIsAECmryoS3puu7FpxvoIhPVkTr22Fic_HOrRycNUmyBwnINAsFEHWI-lKEPsaAhnNEALw_wcB](2019 Qi Wireless Charger PCBA Circuit Board With Coil Charging)

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
