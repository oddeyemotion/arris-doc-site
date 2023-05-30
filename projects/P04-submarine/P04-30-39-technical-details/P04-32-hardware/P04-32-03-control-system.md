---
icon: cpu
label: P04.32.03 Control system
---
# :icon-cpu:⠀Control system
`Tags:` [!badge Submarine](/projects/P04-submarine.md) [!badge robot-car]()

!!!
*More details in future updates*
!!!

### Chassis-mounted circuit
![](/projects/P04-submarine/media/toggle-switch-lmao.jpg)
The chassis mounted circuit is the heart of the robot. It is responsible for controlling all of the robot's components, including the drive motors, the lift system, and the signal communication.

The controller for the chassis mounted circuit is an Arduino Mega 2560. The Arduino Mega 2560 is a powerful microcontroller that can be programmed to control a wide variety of devices. In this case, the Arduino Mega 2560 is programmed to control the drive motors, the lift system, and the signal communication.

The drive motors for the chassis mounted circuit are four gearbox motors with encoders. The gearbox motors allow the robot to move at a variety of speeds, while the encoders allow the Arduino Mega 2560 to track the position of the motors. The drive motors are controlled by two H bridge modules, L298N. The H bridge modules allow the Arduino Mega 2560 to control the direction and speed of the drive motors.

The lift system for the chassis mounted circuit is controlled by a Nema 42 stepper motor that can hold 1kg and a TB6600 stepper motor driver. The stepper motor allows the robot to lift and lower its arm with precision. The stepper motor is controlled by the Arduino Mega 2560 through the TB6600 stepper motor driver.

The signal communication for the chassis mounted circuit is handled by an HC-06 module. The HC-06 module allows the Arduino Mega 2560 to communicate with other devices, such as a computer or a smartphone. The HC-06 module is connected to the Arduino Mega 2560 through the UART port.

The chassis mounted circuit is a complex system that is responsible for controlling all of the robot's components. It is a critical part of the robot and is essential for its operation.

### Gripper module circuit
![](/projects/P04-submarine/media/circuit-temp.jpg)

|
--- | ---

<figure>
    <img src="https://64.media.tumblr.com/d103eb823dce2842c673f409f036857b/tumblr_mzx9wrdwFa1snc5kxo1_1280.gifv" alt="Credit: @transparent-angel on Tumblr">
</figure>