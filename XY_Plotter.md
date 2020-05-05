# **XY Plotter**
**Problem Statement:**
To create a Computer Numerical control machine which is in this case an X–Y plotter.
It is a plotter that operates in two axes of motion ("X" and "Y") in order to draw continuous vector graphics.

**Ideation**

Image &#8658; Gcode &#8658; G-Code Sender &#8658; Arduino(with GRBL firmware) &#8658; Stepper motors and its driver &#8658;
Complex sliding  Mechanical Parts &#8658; Image
 -Stages deciphered
| **Stages** | **Notion** | **Advantage** | **Disadvantage** |
| --- | --- | --- | --- |
| **Image** | An Image to be drawn | Any kind of vector graphic image can be used  | As the complesity increases,time increases |
| **Gcode** | Language that tells computerized machine tools how to make something  | There are various softwares, inbuilt options available in sofwares like Inkscape to convert image to Gcode | Difficult to code manually |
| **G-code Sender** | This software sends the G-code to Microcontroller and configures the setup | This software helps in doing one of the most important part of this project | Difficult to understand and use for Newbies.Especially the configuration part |
| **Arduino with GRBL** | The GRBL(Software) uses G-code as input, and outputs motion control via the Arduino | To build a CNC machine using simple Arduino is just beacuse of this open source software GRBL  | No variables, no tool databases, no functions, no canned cycles, no arithmetic and no control structures. Just the basic machine operations and capabilities.Which will make Human G-coders frustrated |
| **Stepper Motors and its Driver** | Need for the motion of the machine |  Its low speed-high torque enables the use of timing belt.  | There is need of separate driver to control these motors |
| **Mechanical system** | Sliders,belts and beams,etc are the most important components of this whole project | Provides the ability to cover(along with motors) the 2D plane  | **Hell!!** This is going to be toughest part to build in this whole project.If this Mechanical system is not strong enough,then all the above ideations will go vain|
| **Image**| End result | Will look Beautiful :D | If any of the above stages go wrong....Rest is History...!!! |
