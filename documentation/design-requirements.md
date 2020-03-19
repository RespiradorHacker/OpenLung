# Design Requirements

## Drafted by Trevor Smale

### Features and issues found in previous designs

- Great features found in the Rice Design - Easy to use 3 button adjustment scheme (Tidal volume + -), High low pressure alerting, mostly NC fabrication methods, Compact and light.
- Issues found with the Rice Design - Multi Material (Complex construction), Seemingly fragile components, Unventilated/cooled electronics, low humidity tolerance, No proper open source files.
- Great features found in the MIT Design - Ultra reliable cam actuation mechanism, simple/repeatable motor diver circuit, Similar Easy to use 3 button schema, Hermetically sealed.
- Issues found with the MIT Design - Multi Material (Complex construction), Overtly robust/substancial, Some specialty parts.

### Medical

- User-specified breath/min (Via button or knob interface)
insp./exp ratio, tidal volume
- Assist control (Negative pressure detection?)
- Positive end-expiratory pressure (PEEP)
- Maximum pressure limiting
- Humidity exchange (built into the mask)
- Infection control (By way of covering the unit in an easily cleaned enclosure)
- Limited dead-space 

### Electronics and UI/UX
- Spec an interface (LCD and Buttons)
- Spec feedback sensors for PEEP, low voltage, high and low pressure events.
- Outline interface visually

### Mechanical

- Portable / Stationary (Perhaps the stationary design will be a seperate branch)
(Greg: I would index on stationary. The Rice/MIT designs are for dev world. This project assumes use in a resource limited hospital)
- Standalone operation (Full autonomy by way of sensor feedback and adjustment loops)
(I think reaching full autonomy is beyond the scope - the target should be that this is managable with a 1:4 RN:PT ratio)
- Robust mechanical, electrical and software systems (Simple, Corrosion resistant, Vibration resistant, Best crystal oscillator)
- Readily sourced and repairable parts (3D printing)
- Minimal power req (Efficient motor controller)

### Economic

- Low cost ($100.00 US build cost)
- Must fit within standard printer bed
(I would target stamping. The US/Canada has hundreds of stamping shops that can producer stronger parts in faster volumes than 3D printing)
(large enough 3D printers for this are limited, and slow in production. A single stamping shop can make 100s of these a day)
- Must use internationally available 'off the shelf parts'

### User interface

- Alarms for loss of power, loss of breathing circuitintegrity, high airway pressure and low battery life
- Display of settings and status
- Standard connection ports

### Repeatability

- Indicators within 10% of correct reading
- Breath frequency accurate to one breath per minute ( 1 out of approx 30 breaths )