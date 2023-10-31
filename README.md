# Project 1: Duckiebot Square

**Video Link:** [Replace with your video link]

## Objective:
Drive the Duckiebot in a square pattern on the lab floor while integrating LED feedback.

## Instructions:

### 1. Wheel Calibration:
Before starting the project, it's essential to calibrate the wheels to ensure accurate movement. Adjust the resolution parameters in the `wheel_encoder` node.

### 2. Build the Project on the Duckie:
- Run the following commands to build and launch the sample project code:
    ```
    catkin_make
    source devel/setup.bash
    roslaunch project1 project1.launch
    ```
- Ensure that the Duckie changes colors every second.
- Confirm that the color change is logged on the screen.

### 3. Project 1 Code:
Write the code for the Duckiebot to perform the following tasks:

#### a. LED Indication:
Before starting its movement, the Duckiebot should use its LED lights to indicate its intention to move.

#### b. Square Movement:
Drive the Duckiebot in a square pattern present on the lab floor. When the robot comes to a stop:
- The intensity of the rear LEDs should be at its maximum.
- The LED color should be red, mimicking a car's brake lights.

#### c. Post-Movement LED Pattern:
Once the Duckiebot has completed the square, the LED lights should display a cool pattern.

### Submission:

1. Push your code to the repository.
2. Edit this markdown file and update the "video link:" section below with a video showcasing your robot's performance.


