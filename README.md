# MarsRoverChallenge

To run this code, click on open in colab and run each block.

Mars Rover Challenge in Python
The code defines a class called Rover. Each instance of the Rover class represents a rover on Mars. The rover has attributes x and y to store its current position, and direction to store its facing direction.
The Rover class has several methods:
  The move method updates the rover's position based on its current direction.
  The turn_left method rotates the rover 90 degrees to the left.
  The turn_right method rotates the rover 90 degrees to the right.
  The process_instructions method takes a string of instructions and executes them one by one. The instructions can be 'L' (turn left), 'R' (turn right), or 'M' (move forward).
  The get_position method returns a string representation of the rover's current position and direction.
  The run_mars_rovers_challenge function takes two parameters: upper_right and rovers. upper_right is a string representing the size of the Mars plateau, and rovers is a list of lists representing the     initial positions and instructions for each rover.
Inside the run_mars_rovers_challenge function, the upper_right string is split into plateau_x and plateau_y, representing the maximum coordinates of the plateau.
The function then iterates over each rover in the rovers list. For each rover, it splits the initial position and instructions. The position is extracted as x, y, and direction. A new instance of the Rover class is created with these values.
The process_instructions method is called on the rover, passing the instructions. This will execute the instructions and update the rover's position accordingly.
Finally, the get_position method is called on each rover and the result is printed, representing the final position and direction of each rover after executing the instructions.
In this specific example, there are two rovers. The first rover starts at position (1, 2) facing North and follows the instructions "LMLMLMLMM". The second rover starts at position (3, 3) facing East and follows the instructions "MMRMMRMRRM". The final positions of the rovers are printed as output.
