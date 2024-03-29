Project Description:
The project required the development of a programmed robot (eebot) which can navigate a maze
that contains a start and finish line with various obstacles meant to disrupt the robot’s path. To do so, the eebot was programmed in Assembly using the CodeWarrior Integrated Development Environment (IDE). 


Additional Information:

The development took advantage of the robot’s seven photosensors, which used
voltage, current and resistance values, in addition to voltage thresholds, in order to detect the difference between black and white colour. Black lines were used to define the path on which the robot would determine its movement, while the base colour of the maze was white. These contrasting colours made it so that the robot could navigate a path clearly, should the motors and sensors be in working order with the code. While there were various obstacles put in the maze to test the efficiency of the robot in finding a path, the robot had a valid response upon encountering these obstacles. Should the eebot encounter/run into an obstacle, it would perform a 180-degree turn (commonly known as a U-turn) and find another path to eventually reach the finish line. The idealogy behind the robot determining the path to follow is by using the left and right sensors to constantly sweep and find a black line to follow. The frontal sensor was
also used to help the bot continue along a straight line path, allowing for straight and curved lines to be navigated. Moreover, the robot also displayed the current state of operation, sensor configurations (values corresponding to sensor position) and voltage on the LCD while solving the maze.