# FRC-test

<!-- ABOUT THE PROJECT -->
## About The Project

This project intends to explore how easy it can be to get an FRC development environment working. It is intended to be run in the simulator on desktop. While simulating, this project exercises joystick, PWM, and digital inputs and outputs. In teleoperated mode, the PWM is driven both by a joystick and a digital input. Autonomous sets the PWM and digital output for 2 seconds. 


<!-- GETTING STARTED -->
## Getting Started

To get started, we just need to copy the repo to your computer and get VSCode, our development program, set up.

### Prerequisites

Before we get started, install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), [Java SE 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html), and [VSCode](https://code.visualstudio.com/download)

### Installation

1. Git clone this repository into a good location on your computer. Run the following in command prompt while in the location you want to download the project. 
    ```sh
   git clone https://github.com/blaine141/FRC-test.git
   ```

2. Open the FRC-test folder in VSCode
3. You should get a popup asking if you want to install the recommended extensions. Click yes.
4. Click the bug on the left and hit the play button. The simulator should pop up.



<!-- USAGE EXAMPLES -->
## Usage

### Teleoperated

In teleoperated mode, you will control the robot with your joystick. While moving the x ad y axis, the robot will drive and turn. You can view this in the PWM outputs. You can also force the robot to drive by setting the digital input to true. The digital output is linked to the 1st button on the joystick. When the button is pressed, the output is on. NOTE: You must drag a joystick from system joysticks to joysticks for a joystick to be assigned a number.

### Autonomous

In autonomous mode, the robot will drive forward for 2 seconds right after being enabled. While the robot is driving, the digital output will be on.

### Testing

In testing mode, the robot will print the text "Testing!" repeatedly in the console.
