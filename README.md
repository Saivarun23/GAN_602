# GAN_602
Enhancing Detector Performance through Synthetic Data Generation Using Generative Adversarial Networks

Particle detectors are essential in high-energy physics and medical imaging, and material sciences, just like
their testing and calibration, which is very resource-intensive. The project presented herein, Enriching Detector
Performance by Synthetic Data Generation Using GANs, to overcome these challenges using synthesis data generated
via the 2D Convolutional Generative Adversarial Networks. Using voxelized particle shower datasets coming from the
CERN Open Data Portal, the project transforms energy deposition data into 2D projections for effective synthetic data
generation. In this project, the GAN model is trained in order to replicate some key characteristics of the particles'
interactions, while statistical metrics on realism will be assessed by comparing synthetic and real data.

In high-energy physics, medical imaging, and material sciences, particle detectors play a pivotal role in advancing discovery. However, acquiring high-quality experimental data can be resource-intensive and time-consuming. To address this, my project explored synthetic data generation using 2D Convolutional Generative Adversarial Networks (GANs) with data sourced from the CERN Open Data Portal.

Key highlights of the project:
- Data Transformation: Converted 3D voxelized particle shower data into 2D projections to simplify processing while retaining crucial interaction characteristics.
- GAN Architecture: Designed a generator and discriminator to produce synthetic data closely mirroring real detector data.
- Evaluation Metrics: Assessed synthetic data using measures like Mean Squared Error (MSE), Structural Similarity Index (SSIM), and Wasserstein Distance.
 
Results showed promising alignment with real data for general trends, although there's room for improvement in capturing finer structural details. Future work could involve advanced GAN architectures (e.g., attention mechanisms and conditional GANs) to enhance structural fidelity.

This project underscores the potential of synthetic data to streamline detector testing and calibration, making research more accessible and efficient.
