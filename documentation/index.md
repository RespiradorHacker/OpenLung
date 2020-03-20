# Documentation

A work in progress...

## Structure
* [Electronics](/documents/electronics) - All hardware for Controls, User Interface & Motor related documents
* [Software](/documents/electronics) - All software related docs
* [Mechancial](/documents/electronics) - All mechanical related docs

## Requirements

The following were taken from a medium article:
* Be reliable. It must work continuously without failure (100% duty cycle) for blocks of 14 days — 24 hours a day. If necessary, the machine may be replaced after each block of 14 days x 24 hours a day use.
* Provide at least two settings for volume of air/air O2 mix delivered per cycle/breath. These settings to be 450ml +/- 10ml per breath and 350ml +/- 10ml per breath.
* Provide this air/air O2 mix at a peak pressure of 350 mm H2O.
* Have the capability for patient supply pipework to remain pressurised at all times to 150mm H20.
* Have an adjustable rate of between 12 and 20 cycles/breaths per minute.
* Deliver at least 400ml of air/air 02 mix in no more than 1.5 seconds. The ability to change the rate at which air is pushed into the patient is desirable but not essential.
* Be built from O2 safe components to avoid the risk of fire and demonstrate avoidance of hot spots.
* Be capable of breathing for an unconscious patient who is unable to breathe for his or herself. Ability to sense when a patient is breathing, and support that breathing is desirable but not essential.
* Be able to supply pure air and air O2 mix at a range of concentrations including at least 50% and 100% Oxygen. Oxygen shortages are not expected, but the ability to attach a Commercial Off The Shelf (COTS) portable O2 concentrator machine may be a useful feature.
* Support connections for hospital Oxygen supplies — whether driven by piped or cylinder infrastructure
* Be compatible with standard COTS catheter mount fittings (15mm Male 22mm Female)
* Fail SAFE, ideally generating a clear alarm on failure. Failure modes to be alarmed include (but are not limited to) pressure loss and O2 loss

### References
* [Design Requirements](/requirements/design-requirements.md)
* [CSSALTlab Open Source Ventilator](https://github.com/CSSALTlab/Open_Source_Ventilator)
