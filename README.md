# Image-Reconstruction-Using-Hologram-IP-CV-PROJECT-7th-SEM
Accelerating 2D Image-to-Hologram Conversion and High-Fidelity Reconstruction



Overview

This project focuses on generating Computer-Generated Holograms (CGHs) from 2D images and studying their numerical reconstruction. It explores different computational and learning-based approaches to generate holographic phase patterns and reconstruct images through numerical light propagation.

The project investigates four approaches:

1.Phase Retrieval

2.Direct Phase Optimization

3.CNN-Based Phase Prediction

4.Point Cloud-Based Hologram Generation

Objectives

Generate computer-generated holograms from input images.

Reconstruct images numerically using light propagation models.

Explore phase retrieval and direct phase optimization techniques.

Investigate CNN-based phase prediction using PyTorch.

Explore point cloud-based hologram generation.

Compare the reconstructed outputs obtained using different approaches.

Technologies Used

-Python

-NumPy

-Matplotlib

-PyTorch

-Pillow (PIL)

Methodology

1. Phase Retrieval

Phase retrieval iteratively estimates the phase distribution required to reconstruct a target image. The algorithm uses repeated transformations between image and hologram planes to improve the reconstructed output.

2. Direct Phase Optimization

In this approach, the phase pattern is directly optimized by minimizing the difference between the target image and its numerically reconstructed output.

3. CNN-Based Phase Prediction

A Convolutional Neural Network (CNN) is trained using PyTorch to predict phase patterns from input images. The predicted phase maps are then used to obtain numerical reconstructions.

4. Point Cloud-Based Hologram Generation

The point cloud approach represents an object using a collection of 3D points. Each point can contribute to the holographic pattern according to its position, depth, and optical properties. The contributions from the points are combined to generate a hologram, which can then be numerically reconstructed.

The implementation details depend on the point cloud representation and the light propagation model used in the project.

Results-

The generated phase patterns and numerically reconstructed images are analyzed to compare the different approaches.

Phase Retrieval
<img width="1088" height="292" alt="image" src="https://github.com/user-attachments/assets/2b3cd03c-9f8b-4fc1-8b7f-96feb9500835" />




Direct Phase Optimization
<img width="964" height="298" alt="image" src="https://github.com/user-attachments/assets/d5a665e8-d593-4624-9be4-ca558418f2c5" />




CNN-Based Phase Prediction
<img width="1110" height="380" alt="image" src="https://github.com/user-attachments/assets/12ebe049-1b4c-4beb-b7d3-296f8943e1b6" />




Point Cloud-Based Hologram Generation
<img width="1084" height="306" alt="image" src="https://github.com/user-attachments/assets/3b666639-2022-41eb-a522-fe7a23ec7db3" />

