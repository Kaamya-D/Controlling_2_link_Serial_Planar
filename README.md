# Controlling_2_link_Serial_Planar
## Project Overview
This project implements and analyzes the control of a two-link robotic manipulator using various control strategies, including Proportional (P), Proportional-Integral (PI), Proportional-Derivative (PD), and Proportional-Integral-Derivative (PID) controllers. The objective is to bring the joint angles of the manipulator from an initial position to a desired position using MATLAB simulations.



## Implementation
The system is modeled and simulated in MATLAB. The project consists of:
1. **Modeling the two-link manipulator using Euler-Lagrange equations**
2. **Implementing PID control strategies**
3. **Simulating and analyzing the system response for different controller settings**
## Results and Analysis
### Controllers Implemented
- **P Controller:** Reacts to the current error and leads to steady oscillations.
- **PI Controller:** Eliminates steady-state error but may lead to oscillations.
- **PD Controller:** Improves stability and reduces overshoot.
- **PID Controller:** Provides the best response with minimal error and overshoot.

### Simulink Block Diagram
The control system was also implemented in Simulink using blocks for PID control.

## Conclusion
The PID controller was found to offer the best overall performance for controlling the robotic manipulator, ensuring smooth and accurate trajectory tracking with minimal overshoot and steady-state error.

## Future Work
- Implementing adaptive control strategies for better performance.
- Using reinforcement learning for optimizing PID gains dynamically.



![image](https://github.com/user-attachments/assets/6e0c6b84-be04-428b-aed8-e6c4557f3564)
![image](https://github.com/user-attachments/assets/d63d4ba6-8dd8-46a8-a5ed-9dc6ba3d7f41)
![image](https://github.com/user-attachments/assets/02a1db5a-0ebe-4708-ae93-d1798fbfc24b)

![image](https://github.com/user-attachments/assets/1d08b243-4902-4bc6-99b6-c062815ced80)

![image](https://github.com/user-attachments/assets/9c751f89-4c85-48bc-98a7-7c9f2d213896)
![image](https://github.com/user-attachments/assets/25cbc7f0-7c74-4eef-a2bf-28b6e77e6748)
![image](https://github.com/user-attachments/assets/ef36ecc9-ef7b-430b-960b-3fd2368e993b)
![image](https://github.com/user-attachments/assets/02e4410b-6006-4be1-b83b-bdaf678adfe7)
![image](https://github.com/user-attachments/assets/34419b5e-5e18-4b7e-937b-f264930640ac)
