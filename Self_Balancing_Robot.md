# **Self-Balancing Robot**
**Problem Statement:**
To create a 2-Wheeled Robot that balances itself even under external disturbances

**Ideation**

MPU6050 Gyroscope and Accelerometer sensor &#8658; Microcontroller &#8658; Motors 

**Stages deciphered**
| **Stages** | **Notion** | **Advantage** | **Disadvantage** |
| --- | --- | --- | --- |
| **MPU6050** | 3-axis gyroscope and a 3-axis accelerometer | Provides the data/values needed  | Difficult to understand how to extract the info intially.Only reading the raw value is easy |
| **Microcontroller** | All the processing is done in this part.PID controller can be implemented  | Several Libraries are out there for Arduino that can be used in this project | The coding part is confusing as MPU6050 is used |
| **Motors and Its driver** | Motors help to balance this bot.Stepper motor/DC Motors can be used | Easiest part to handle and understand | If stepper motors are used,its going to cost a bit high |

**Scopes of Improvement:**
* This robot can be improvised to carry objects from one place to another
* Can introduce a Bluetooth Module to control these bot to move.

\
*This project will mostly end by prototyping phase.If we wanted to make a robust model we can move onto Manufacturing Phase.*
