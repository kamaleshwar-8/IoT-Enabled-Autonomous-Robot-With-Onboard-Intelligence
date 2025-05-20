## Overview
This repository contains the implementation of an IoT-enabled autonomous surveillance robot with onboard path planning capabilities and remote image classification. The robot leverages the ESP32-CAM module to simultaneously stream real-time video to a web interface accessible to the user and autonomous navigation using the A* algorithm that moves the robot in a grid-like fashion. The image shows live navigation of the robot and the results of image classification.
## Key Features

- Real-Time Video Streaming: ESP32-CAM module provides live video feed to a web interface
- Autonomous Navigation: Implementation of A* algorithm for grid-based path planning and movement
- Motor Control System: PWM signal generation through L293D motor driver for precise movement
- Dynamic Camera Positioning: Servo motor enables camera panning for expanded surveillance coverage
- Remote Image Classification: CNN model deployed on an attached computer to classify objects within the camera's field of view
- Web Interface Control: User-friendly interface for remote robot control and image classification triggering
## Result
- Live streaming feature
  
  ![fig1](https://github.com/user-attachments/assets/6f7e7156-517b-4abb-bbd4-123beeb3d822)
- Manual control options
  
  ![fig2](https://github.com/user-attachments/assets/4c43ecbf-f301-437d-8354-2c138394a53b)

- Robot at initial position
  ![fig3](https://github.com/user-attachments/assets/09396d1f-b924-4810-bcc9-e0234b58ede5)
  
- Robot while navigating
  ![fig4](https://github.com/user-attachments/assets/792107f8-92f8-48dd-aa2d-962c72af424f)

- Image Classification
  ![fig5](https://github.com/user-attachments/assets/8000f10f-824b-42d4-897c-549fd8e4f4d5)
