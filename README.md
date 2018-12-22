# PIC MOTOR CONTROLLER FOR BLDC MOTOR

## The goal of the final project was to design a system that took in real world data, ana-lyzed that data, controlled something as a result of that data, and communicate witheither a computer or through wireless means.  The system that was created was aMotor Controller for a brushless DC (BLDC) motor capable of communicating overa Controller Area Network (CAN) using Microchip’s dsPIC33EV256GM102 and CANtransceivers.

### On a top level view, the system reads a potentiometer value and the motor will spinat a speed consistent with that value.  This works with the motor under load so thatit can actually be used.  This can be achieved due to the nature of the closed loopsystem under which the motor is operating.  The motor reports its speed back to themicrocontroller and there it is determined whether the motor needs to spin faster orslower. This will be explained in more detail later in the report.
