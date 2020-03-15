Ok, so I am not very knowledgeable when it comes to small electric motors, Though I think based on the points below that using a servo motor is most suitable for this project.

# Types of Motors

## 1. Brushed and Brushless DC Motors
DC motors are electromagnetic devices that use the interaction of magnetic fields and conductors to convert electrical energy to mechanical energy for rotation. There are many types of DC motors out in the market. The brushed and brushless motors are the most common DC motors.

Brushed DC Motors
The brushed DC motor have been around for a long time, and its use can be traced back to the 1830s. They can be found just about anywhere. In toys, household appliances, computer cooling fans, you name it. As one of the simplest motors to construct and control, it is no wonder that the brushed DC motor still remains as a favorite among professionals and hobbyists alike.
Why are they called brushed motors? The current is provided via two stationary metallic brushes that make contact with the different segments on the ring. As the commutator rotates, the brushes make contact with the next segment and therefore continue the rotation of the motor. As you can imagine, this generates friction and so heat and even sparks are generated.
How does a DC motor move? DC motors consist of coils connected to segments of a ring, or commutator. The coils are surrounded by a pair of magnets, or a stator, that envelopes the coils in an electric field. If you remember from your physics classes, when current is passed through a wire in a magnetic field, the wire experiences a force, and so the coils in the motor experience a force that pushes the coil and begins the rotation. The GIF illustrates the working principle of the brushed motor. The coil experiences a downward force when it reaches the area on the right, and an upward force when it reaches the area on the left. By adding multiple coils attached to different segments on the commutator, steady rotation can be maintained. The direction of rotation can be reversed simply by reversing the polarity on the motor’s contacts.

### Advantages & Limitations:

### Advantages

* Simple to control Controlling a brushed DC motor is as simple as a switch. Simply apply a voltage to start driving them. They slow down when the voltage is lowered, and spin in the other direction when the voltage is reversed.
* Excellent torque at low speeds
* High torque is achieved at low speeds.
* Reasonably Efficient
* Brushed DC motors are about 75-80% efficient.
* Inexpensive, A typical brushed DC motor at the Seeed Bazaar costs only $2.55.

### Limitations

* Noise
* Aside from the audible noise from the rubbing parts, electromagnetic noise is also generated as a result of the strong sparks that occur at areas where the brushes pass over the gaps in the commutator. This can potentially cause interference in other parts of the system.
* Constant Maintenance
* Brushes could get easily worn out as a result of continuous moving contact and require constant maintenance. Speed could be limited due to brush heating.

### Brushless DC Motors

Brushless DC motors are mechanically simpler than brushed ones. As commutation is achieved electrically, the sparks and noise of brushed DC motors is eliminated, enabling the current flow to switch silently and therefore allowing the motor to be driven quietly. These quiet motors find applications in computer fans, disk drives, drones, electric vehicles and high-precision servomechanisms. The brushless DC motor only has one moving component – the rotor, which eliminates the complications caused by brushes in brushed motors. And also unlike brushed motors, the rotor consists of a ring of permanent magnets, whereas the coils are stationary. This set-up eliminates the need for brushes. The difficult part comes in controlling the polarity of the current flowing through the coils and keeping this in sync with the speed of the rotor. This can be achieved by measuring back EMF or using Hall effect sensors to directly measure the position of the magnets. Due to this, brushless DC motors are typically more expensive and complex, in spite of the numerous advantages it has over brushed DC motors.

### Advantages & Limitations:
### Advantages

* Quiet, They generate less electrical noise compared to brushed motors as no brush is used. Hence, brushless DC motors are often preferred in applications where it is important to avoid electrical noise.
* Efficient, Brushless DC motors are more efficient than brushed motor, as they are able to continuously achieve maximum rotational force/torque. Brushed motors in contrast, will reach maximum torque only at certain points during the rotation. For a brushed motor to achieve the same torque as a brushless motor, it would require a larger magnet.
* Require less maintenance Brushless DC motors offer high durability as there are no brushes to be replaced.

### Limitations

* Controller, Some brushless motors are difficult to control and require a specialized regulator


