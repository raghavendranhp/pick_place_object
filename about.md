#  PICK AND PLACE OF OBJECT



## OBJECTIVE:
This document outlines the process of simulating a Pick and Place operation using the Doosan Robotics M1013 White Robot in RoboDK. It provides a step-by-step guide to configuring the robot, setting up reference frames, and programming movement sequences to achieve a successful pick-and-place operation.

## SOFTWARE AND HARDWARE REQUIREMENTS:
**SOFTWARE:** RoboDK  
**OS:** Windows Vista/7/8/10/11 (32-bit or 64-bit), Mac OS (64-bit), Ubuntu 16/18 (64-bit)  
**PROCESSOR:** Intel Core i3 or equivalent  
**MEMORY:** Minimum 2 GB RAM (4 GB recommended)  
**GRAPHICS PROCESSOR:** OpenGL 3.0 compatible, Intel UHD or better  
**STORAGE:** 15 GB total, 1 GB free space

---

## PROCEDURE:
1. **In RoboDK:**
   - Download and load the required robot and components into the workspace.
   - Organize objects and set up frames to define reference positions.

2. **Frame and Object Setup:**
   - Create and name reference frames for base and target positions.
   - Arrange components within the frames and reset their positions.

3. **Robot Positioning and Adjustments:**
   - Configure the robot's base and joint angles for optimal alignment.
   - Adjust positions of parts and objects to match the desired operation layout.

4. **Teaching Targets:**
   - Define key targets (home position, pick, and place points) for the robot's movements.
   - Use coordinate adjustments to ensure accurate positioning.

5. **Program Creation:**
   - Develop separate programs for resetting, picking, and placing operations.
   - Use simulation event instructions to attach and detach objects dynamically during movements.

6. **Main Program Setup:**
   - Combine individual programs into a main sequence to automate the pick-and-place process.

7. **Simulation and Testing:**
   - Execute the main program to test the complete sequence.
   - Verify smooth transitions and adjustments as needed.

---

## OUTPUT:
Successfully simulated the Pick and Place operation using RoboDK.

## RESULT:
The Pick and Place operation was successfully implemented and tested in RoboDK.

## INFERENCE:
1. Learned the importance of defining reference frames for robot positioning and alignment.
2. Understood how to attach and detach objects programmatically during simulations.
3. Gained hands-on experience in programming robotic movement sequences.
4. Improved ability to manage and simulate complex robotic operations in RoboDK.
5. Developed practical insights into joint and linear movements for precise trajectory planning.

