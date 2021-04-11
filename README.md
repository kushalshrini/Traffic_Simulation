# Traffic_Simulation
Developed a motion of a car in response to traffic lights Using OpenGL. We have three lights in the signal Red, Green and Yellow. Each light has some meaning . Red means stop , Green means go, Yellow means ready to go.

As we know, the traffic signals direct the flow of traffic with the exemption of signals with turning arrows which should be compulsory in accord with each other.Traffic signals help us to drive our vehicles in a safer manner lowering the risk of accidents, if properly followed.

Same method we implemented in our project which was used in real life .We have used this traffic signal in a cross road to avoid mishappening. When there is a green signal it means the vehicle can move or run on the road but if this green signal turns off and the red signal is turned on then it indicates the driver to stop his vehicle and at the same time signal allows some other side vehicle to cross the road. But if the vehicle is in the middle of a cross or vehicle has crossed the signal then there is no meaning of red light for the driver. When we press left mouse click then red light will glow and all vehicles are stopped and when we press and hold right mouse click then yellow light will glow and all vehicles ready to go .When we release the right mouse click then green light will glow and then the vehicle starts moving.

## METHODOLOGY

### ALGORITHM:

  ➔ Line drawing algorithm for traffic light pole and body of the car.
  
  ➔ Circle drawing algorithm for wheels of the car and lights of the traffic pole.
  
  ➔ Flood fill algorithm for colouring.

### LANGUAGE:

  ➔ C++ using OpenGL API for graphics

### TOOLS USED: CodeBlocks
● It can create native Win32 executables, either console or GUI, as well as DLLs and static
libraries.

● The application is platform independent.

● C++ was chosen to code the project as it is the most commonly used language in conjunction with OpenGL.


## Features 
Some of the features is listed below -

1.**Light Options** - As in any traffic signal you will see the three lights - red, yellow and green. All the options has been implemented.

2.**Vehicles** - To keep the OpenGL Code simple for all only three vehicles has been added. Though, if you like to add more do it, you are welcome.

3.**Lanes** -  The right and left lane options is implemented in the program.

4.**User Interactions** - Both mouse and keyboard interaction has been added to the OpenGL Code. All the user interactions has been listed in the post below.

5.There is options to speed up the traffic is also in the code.

6.Program has include the front page for introduction.


## User Interactions

## Keyboard Interactions

  ➔ **Enter** - From First Introduction screen to screen press Enter key at beginning.

  ➔ **Help** -  Press 'h'to get the help screen.

  ➔ **Left to right movement** - press 'l' to allow only left to right movement of traffic.

  ➔ **Right to left movement** - press 'r' to allow only right to left movement of traffic.

  ➔ **Speed up** - To speed up the traffic press 's'.

### Mouse Interactions

  ➔ **Left Mouse Button** - This will stop the traffic as Red light gets on.

  ➔ **Right Mouse Button (on hold)** - Press right mouse button and keep on hold for yellow light. 

  ➔ **Right Mouse Button (released)** - After releasing the right mouse button the light changes from yellow to green and traffic moves.
