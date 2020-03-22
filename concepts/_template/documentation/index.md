# Documentation

A work in progress...

## Structure
* [Electronics](/documents/electronics) - All hardware for Controls, User Interface & Motor related documents
* [Software](/documents/electronics) - All software related docs
* [Mechancial](/documents/electronics) - All mechanical related docs

## Requirements

### Ventilator Specifications
Three common modes of control in Ventilators:
* Volume Control
* Pressure Control
* Pressure Regulated Volume Control (PRVC)

|Control|Range|Accuracy|Settings|Default|Notes|
|---|---|---|---|---|---|
|Tidal Volume (V<sub>T</sub>)|4-6ml/Kg IBW*<br>(205 - 530ml)|±???|±1ml/Kg<br>(35ml)|-|
|Respiratory rate|15-35bpm|???|±2bpm|15bpm
|I:E Ratio|1:1 - 1:2|???|???|
|Plateau Airway Pressure (P<sub>AW</sub>)|???-35cmH<sub>2</sub>O|???|???|< 30cmH<sub>2</sub>O|If > 35 V<sub>T</sub> needs to be decreased to 5 or 4ml/Kg IBW
|Driving Pressure<br>(P<sub>AW</sub>-PEEP)|???-15cmH<sub>2</sub>O|???|???| |PEEP may be fixed???|
|PEEP|5-24|???|±1|???|

(*)Calculate Ideal Body Weight (IBW, Kg) using patient height (cm):

|Male|Female|
|---|---|
|= 50+0.91x(height in cm-152.4)|= 45.5+0.91x(height in cm-152.4)

### Cycling of the Mechanical Ventilator Breath
The change from inspiration to expiration is a crucial point in the mechanically ventilated breath, and is termed "cycling".

Cycling Mechanisms:
* Pressure
* Time
* Volume
* Flow


## Posted by [@Cullen Powell](https://app.slack.com/team/U010CERKB0U) on [Slack](https://osventilator.slack.com/archives/C0103CK03RC/p1584662845336700)

Proposal for criteria a medium equipped situation ventilator should meet:

Background situation:
1. Medical staff trained with ventilation in short supply of machines
2. Oxygen available
3. Electric power available
4. The device should be able to provide:
* pressure controlled ventilation,
* adjustabe PEEP (positive end respiratory pressure)
* adjustable oxygen concentrations from 21 to 100%
* setting of p max, peep, i:e, o2concentration,
* measurement of actual o2 concentration in airway
* measurement of actual airway pressures
* alarms on o2 failures
* alarms on electric failure
* alarms on pressure limit violation, including setting of these
* battery buffer to overlap electric blackout (5 - 120 min)
* hygienic conditions for all part that are in contact to patients breath
* sufficient electric safety
5. The device should be producable in nummers of 10,000s
6. sustainable for active time larger than 180 day constant work and be desinfectable
Ventilators are part of a complex treatment situation.
There are professionals (doctors, nurses, paramedics, etc.) who identify the right patient,
and give them treatment with sedation (iv-line, cvc), a bed in a suitable set-up, airway sucction device at hand, intubate patients, and controlling the appropiate setting of the ventilator.
- Tretment will take days, or weeks. Withdrawal is an essential part of treatment, reintubation might occur.
7. What is technical crucial to avoid:
* undetected failures -> arlarms
* break of hygiene
* peaks in pulmonary pressure
* overventilation
* underventilation
Ambu-Bags are wonderful for short time treatment.
State of the art ventilators are working on pressure and valve regulations with no mechanical elements, the are doing it fine.

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

### References
* [Design Requirements](/documents/design-requirements.md)
* [University College Cork Covid-19 Resource Centre](https://ucc.instructure.com/courses/22984)
* [UCC Covid-19 Critical Care](https://ucc.instructure.com/courses/22984/pages/critical-care)
* [UCC Covid-19 induced ARDS - protective lung ventilation (Meeke 2020)](https://ucc.instructure.com/courses/22984/files/1700272/download?wrap=1)
* [The Center for Safety, Simulation and Advanced Learning Technologies](https://simulation.health.ufl.edu/technology-development/open-source-ventilator-project/)
* [CSSALTlab Open Source Ventilator - Github repo](https://github.com/CSSALTlab/Open_Source_Ventilator)
* [Pressure Regulated Volume Control (PRVC): Set it and forget it?](https://www.sciencedirect.com/science/article/pii/S2213007118303757)
* [Cycling of the Mechanical Ventilator Breath](http://rc.rcjournal.com/content/56/1/52)
