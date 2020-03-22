# Design Requirements

## Drafted by Trevor Smale (adapted from MIT)

### Features and issues found in previous designs

- Great features found in the Rice Design - Easy to use 3 button adjustment scheme (Tidal volume + -), High low pressure alerting, mostly NC fabrication methods, Compact and light.
- Issues found with the Rice Design - Multi Material (Complex construction), Seemingly fragile components, Unventilated/cooled electronics, low humidity tolerance, No proper open source files.
- Great features found in the MIT Design - Ultra reliable cam actuation mechanism, simple/repeatable motor diver circuit, Similar Easy to use 3 button schema, Hermetically sealed.
- Issues found with the MIT Design - Multi Material (Complex construction), Overtly robust/substancial, Some specialty parts.

### Medical

- User-specified breath/min (Via button or knob interface)
insp./exp ratio, tidal volume
- Support modes PCV   (Presure Controled Ventilator) and VCV  (Volume Control Ventilator ) with assist control. (assist control is the action of detect pacient effort to breath. and it is works in diferent ways acording to ventilator mode)
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

- Alarms for loss of power, loss of breathing circuit integrity, high airway pressure and low battery life
- Display of settings and status
- Standard connection ports
- Button/Control Lock-out to protect accidental adjustment

### Repeatability

- Indicators within 10% of correct reading
- Breath frequency accurate to one breath per minute ( 1 out of approx 30 breaths )

## Posted by @Simon Kiersey on Slack (adapted from Medium article (need source)

- Be reliable. It must work continuously without failure (100% duty cycle) for blocks of 14days — 24 hours a day. If necessary, the machine may be replaced after each block of 14 days x 24 hours a day use.
- Provide at least two settings for volume of air/air O2 mix delivered per cycle/breath. These settings to be 450ml +/- 10ml per breath and 350ml +/- 10ml per breath.
- Provide this air/air O2 mix at a peak pressure of 350 mm H2O.
- Have the capability for patient supply pipework to remain pressurised at all times to 150mm H20.
- Have an adjustable rate of between 12 and 20 cycles/breaths per minute.
- Deliver at least 400ml of air/air 02 mix in no more than 1.5 seconds. The ability to change the rate at which air is pushed into the patient is desirable but not essential.
- Be built from O2 safe components to avoid the risk of fire and demonstrate avoidance of hot spots.
- Be capable of breathing for an unconscious patient who is unable to breathe for his or herself. Ability to sense when a patient is breathing, and support that breathing is desirable but not essential.
- Be able to supply pure air and air O2 mix at a range of concentrations including at least 50% and 100% Oxygen. Oxygen shortages are not expected, but the ability to attach a Commercial Off The Shelf (COTS) portable O2 concentrator machine may be a useful feature.
- Support connections for hospital Oxygen supplies — whether driven by piped or cylinder infrastructure
- Be compatible with standard COTS catheter mount fittings (15mm Male 22mm Female)
- Fail SAFE, ideally generating a clear alarm on failure. Failure modes to be alarmed include (but are not limited to) pressure loss and O2 loss