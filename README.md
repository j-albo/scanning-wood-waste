## Introduction

Currently, only 15% of wood waste is recycled globally, while up to 60% of felled trees remain unused. Many irregular pieces that do not meet industrial standards are discarded without leveraging their structural and aesthetic potential.

![SW-02-2048x563](https://github.com/user-attachments/assets/040c553e-d094-42d6-96aa-7f886d73360e)

Our goal is to rethink these waste materials through scanning, analysis, and digital transformation, converting them into adaptable and structurally viable architectural materials.

![SW-03-2048x747](https://github.com/user-attachments/assets/6a938a18-a0bf-4978-b0c5-6dd889b274bd)

Repurpose discarded wood by transforming and reshaping non-standard logs into structural and adaptable architectural materials.

To be able to use and transform non-standard wood, we first need to scan and understand its anatomy and internal composition.

![SW-02-2048x563](https://github.com/user-attachments/assets/4218334b-ac3c-4875-b28e-5c867cc365e5)


## Workflow

1. **Scanning Methods:**
   - **Photogrammetry & LIDAR:** Capturing the irregularities of logs and analyzing their fibers, axes, and structural properties.
   - **Computer Vision & Stereo Vision:** Complementing the 3D analysis of discarded wood.

2. **Transformation Process:**
   - **Modeling with Grasshopper & Polycam 3D Scanner:** Generating meshes from the initial scans.
   - **Optimizing the Scanning Path:** Planning the ideal route to accurately capture each piece's geometry.
   - **Data Conversion for ROS & MoveIt!:** Transforming scan coordinates into trajectories for simulation and robotic manipulation.

![SW-05-2048x589](https://github.com/user-attachments/assets/a3195f5e-ce77-430d-ba76-0e8ffd946dc6)

## Scanning Toolpath
![SW-06-2048x552](https://github.com/user-attachments/assets/d6b666f7-ee4b-4614-9771-8f8e5f6048bb)
![Grabacin2025-03-08142506-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/74239dc8-8f71-4733-a0fb-6c1539f06d9d)

## Integration with ROS

A key part of the project is the integration with ROS (Robot Operating System) for automated processing and manipulation of wooden pieces.

1. **Environment Setup:**
   - Import necessary libraries for ROS and MoveIt!.
   - System initialization and sensor calibration.

2. **Simulation and Trajectory Planning:**
   - Creating scanning trajectories using circular bounding boxes.
   - Generating waypoints based on the positions and orientations of each piece.
   - Validation and adjustment in MoveIt! and RVIZ to ensure the accuracy of digital transformation.
   - 
![SW-07-2048x410](https://github.com/user-attachments/assets/6dbb22cc-2ac5-4ddf-af06-3c27f48d61ef)
![SW-08-2048x1027](https://github.com/user-attachments/assets/feaf6793-e4aa-4b25-a906-e9ccb949912a)

## Scanning
![ezgif com-video-to-gif-converter-1](https://github.com/user-attachments/assets/8df4b378-d8de-441c-bb4b-9e76c0302114)

## Comparison

![ezgif com-video-to-gif-converter-1-1](https://github.com/user-attachments/assets/0ac0980b-c965-4f1c-9598-c52140e22872)


## Future Steps

This project demonstrates how the combination of scanning technologies, computer vision, and robotics can redefine the use of discarded materials in construction. By turning wood waste into viable structural components, we not only reduce environmental impact but also open new possibilities for adaptable and sustainable architectural design.

The future of digital construction lies in the intelligent reuse of materials, and this project is a clear example of how technology can act as a catalyst for innovation in architecture.

![SW-09-2048x717](https://github.com/user-attachments/assets/568099fd-b34e-4e1a-b034-8a445bc56b83)

---

## Authors

- [Charlie](https://github.com/Clarrainl) 
- [Javi](https://github.com/j-albo) 
- [Mau](https://github.com/Mauweberla) 

*This project was developed as part of the Master in Robotics and Advanced Construction (MRAC), Term II, 2024/25.*

---

