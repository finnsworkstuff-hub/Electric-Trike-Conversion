# Electric-Trike-Conversion

The aim of this project was to convert a conventional tricycle into an electrically powered vehicle for commuting and leisure use. The goal was to increase range, improve hill-climbing ability, and gain hands-on experience with DC motor control, battery systems, and power management.

I chose a 1 kW front hub motor kit paired with a 48 V 20 Ah YosePower lithium-ion battery. This setup offered a balance between performance and range, with an energy capacity of ~960 Wh. 

-----

Motor Installation

The hub motor is mounted directly in the rear wheel, which eliminates the need for a traditional drivetrain. It provides direct torque to the wheel and is controlled electronically through a motor controller. That setup gives around 960 watt-hours of capacity, which is a decent range for cruising or commuting. The whole system runs on DC. The motor uses hall effect sensors, which are essentially small magnetic sensors built into the motor casing. These sensors detect the position of internal permanent magnets as the wheel turns. That position data is used by the motor controller to time the electrical pulses sent to the copper windings, which creates the rotational magnetic fields that spin the wheel. It’s like a timing system that controls the rotation based on real-time magnetic feedback. It keeps the power delivery smooth and stops the motor from cogging or skipping (precise feedback system).

-----

Battery Mounting

The 48 V 20 Ah lithium-ion battery was mounted low on the rear frame of the trike to optimize stability and weight distribution. Positioning the mass centrally between the two rear wheels lowers the center of gravity and reduces lateral load transfer, which improves handling and minimizes vibration-induced disconnection events commonly observed in retrofit e-bike systems. The battery pack is secured to a fabricated steel mounting plate using saddle clamps bolted to the rear axle housing. Stainless-steel fasteners with silicone-threaded lock nuts were employed to prevent loosening under dynamic loading conditions. The rigid mounting and wide base support limit displacement during shock loads (e.g., when traversing uneven terrain), thereby reducing the risk of intermittent power cut-outs due to connector or BMS interruptions.

----- 

Controller Placement

The motor controller was mounted centrally below the handlebars to balance accessibility, visibility, and wiring efficiency. This position places the digital display (battery status and operating modes) within the rider’s natural line of sight, improving operational ergonomics and safety. All leads were routed along the frame and secured using cable ties and flexible wire shielding to minimize free-hanging conductors. This arrangement reduces the risk of mechanical abrasion, mitigates electromagnetic interference between signal and power lines, and prevents cable entanglement with moving parts. Bundling cables also shortens effective wire runs, thereby limiting resistive losses. According to Ohm’s law and the resistivity relation, minimizing conductor length reduces total resistance and hence voltage drop, ensuring efficient delivery of power from the battery to the controller and motor. Although the controller’s enclosure lacks full waterproofing, its central and elevated mounting reduces exposure to splash and road spray. However, the absence of ingress protection (IP rating) remains a limitation. Future iterations could employ a sealed housing or conformal coating to enhance environmental durability. Thermal management was also considered. Since controllers generate heat due to conduction and switching losses, the placement in open airflow assists passive cooling during operation.

-----

Wiring

Connected battery → controller, controller → motor, and integrated throttle/brake levers.
