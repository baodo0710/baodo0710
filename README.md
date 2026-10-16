# Bao Do

M.S. candidate in Mechatronics and Robotics at NYU Tandon School of Engineering.  
Expected graduation: May 2027.

I build learning-enabled robotic systems that remain useful beyond idealized
simulation by accounting for state-estimation error, contact uncertainty,
actuator limits, and hardware constraints.

My current work focuses on legged locomotion, state estimation, and
deployment-oriented validation for quadrupedal and humanoid robots.

## Research Interests

- **Legged and humanoid locomotion** — reinforcement-learning-based control,
  gait shaping, and robustness under real-world constraints.
- **State estimation for legged robots** — IMU integration, leg odometry,
  contact constraints, and Kalman filtering.
- **Learning-based control under imperfect observations** — delayed, noisy, and
  partially observable sensing.
- **Deployment-oriented robotics** — embedded control, sensor integration, and
  hardware-aware validation.

## Featured Projects

### [Rex-Loco-Deploy](https://github.com/baodo0710/rex-loco-deploy)

A platform-adapted reinforcement-learning locomotion and deployment framework
for a 12-DOF, MG996R-actuated SpotMicro-class quadruped.

- Isaac Lab-based PPO locomotion training.
- MG996R-inspired torque-speed saturation modeling.
- ONNX export and PyBullet cross-simulator evaluation.
- Jetson Orin Nano to STM32 deployment interface.
- Servo calibration, joint-limit clipping, communication watchdog, and safe-pose
  recovery.

### [G1 Estimation-Aware Locomotion](https://github.com/baodo0710/g1-estimation-aware-locomotion)

A research project investigating locomotion policies trained without direct
privileged base-velocity observations.

- Replaces simulator ground-truth base velocity with an estimated observation.
- Fuses IMU integration with stance-leg odometry using a per-axis Kalman filter.
- Uses IMU, joint-state, and noisy contact observations.
- Investigates robustness under accelerometer bias and contact-label noise.

## Technical Toolkit

**Robot learning**  
Python · PyTorch · PPO · Isaac Lab · Isaac Sim · domain randomization

**Estimation and robotics**  
Kalman filtering · IMU integration · leg odometry · forward/inverse kinematics ·
Jacobians · contact constraints

**Simulation and deployment**  
MuJoCo · PyBullet · ONNX · Jetson Orin Nano · STM32 · PCA9685

**Embedded systems**  
C/C++ · Python · I²C · SPI · UART · sensor integration

## Contact

- Email: [donguyenbao0710@gmail.com](mailto:donguyenbao0710@gmail.com) | [bd2688@nyu.edu](mailto:bd2688@nyu.edu)
- LinkedIn: [linkedin.com/in/bao-do-86829a222](https://www.linkedin.com/in/bao-do-86829a222)
