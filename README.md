# Low resource Ambu-Bag ventilator

This project was jumpstarted by the COVID-19 global pandemic as a result of community discussion on a facebook group called Open Source COVID19 I created this GitLab project. More specifically in a discussion surrounding low cost AmbuBag based emergency respirators wherein to prior solutions were developed. The first from an MIT research group comprising of the following persons (Abdul Mohsen Al Husseini1, Heon Ju Lee1, Justin Negrete, Stephen Powelson, Amelia Servi, Alexander Slocum and Jussi Saukkonen). The second device from a Rice University Mechanical Engineering student group comprising of the following persons (Madison Nasteff, Carolina De Santiago, Aravind Sundaramraj, Natalie Dickman, Tim Nonet and Karen Vasquez Ruiz. Photo by Jeff Fitlow). This project seeks to combine and improve the efforts of these two projects into a more simple and reliable device that consists mostly of 3D printed parts.

## Reasons for using an Ambu-Bag
- Mass Produced
- Certified components
- Small and Simple mechanical requirements
- Previous research and testing in this area
- Adaptable to both invasive tubing and masks

## Project TO-DO

- Design a more integral 3D printed actuation mechanism
- Spec a good low amperage, high torque DC motor
- Design or find and H Bridge rectifier circuit
- Spec an interface (LCD and Buttons)
- Spec feedback sensors for PEEP, low voltage, high and low pressure events.
- Outline interface visually

Here are links to information found:

* http://news.mit.edu/2010/itw-ventilator-0715
* https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf
* https://news.rice.edu/2019/05/01/student-invention-gives-patients-the-breath-of-life-2/
* http://oedk.rice.edu/Sys/PublicProfile/47585242/1063096
* https://www.instructables.com/id/The-Pandemic-Ventilator/?fbclid=IwAR2E_dr2P2oa6zYFJRhp58rctGrRDLG9AprXnsoJ2JTREiX16TMiPbK_LNs

## Requirements list (Mostly appropriated from the MIT group whitepaper)

### Features and issues found in previous designs

- Great features found in the Rice Design - Easy to use 3 button adjustment scheme (Tidal volume + -), High low pressure alerting, mostly NC fabrication methods, Compact and light.
- Issues found with the Rice Design - Multi Material (Complex construction), Seemingly fragile components, Unventilated/cooled electronics, low humidity tolerance, No proper open source files.
- Great features found in the MIT Design - Ultra reliable cam actuation mechanism, simple/repeatable motor diver circuit, Similar Easy to use 3 button schema, Hermetically sealed.
- Issues found with the MIT Design - Multi Material (Complex construction), Overtly robust/substancial, Some specialty parts.

### Medical

- User-specified breath/min (Via button interface)
insp./exp ratio, tidal volume
- Assist control (Negative pressure detection?)
- Positive end-expiratory pressure (PEEP)
- Maximum pressure limiting
- Humidity exchange (built into the mask)
- Infection control (By way of covering the unit in an easily cleaned enclosure)
- Limited dead-space 

### Mechanical

- Portable / Stationary (Perhaps the stationary design will be a seperate branch)
- Standalone operation (Full autonomy by way of sensor feedback and adjustment loops)
- Robust mechanical, electrical and software systems (Simple, Corrosion resistant, Vibration resistant, Best crystal oscillator)
- Readily sourced and repairable parts (3D printing)
- Minimal power req (Efficient motor controller)

### Economic

- Low cost ($100.00 US build cost)
- Must fit within standard printer bed
- Must use internationally available 'off the shelf parts'

### User interface

- Alarms for loss of power, loss of breathing circuitintegrity, high airway pressure and low battery life
- Display of settings and status
- Standard connection ports

### Repeatability

- Indicators within 10% of correct reading
- Breath frequency accurate to one breath per minute ( 1 out of approx 30 breaths )
