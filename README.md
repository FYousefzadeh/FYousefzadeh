# 👋 Farnaz Yousefzadeh

I work on deep learning and medical image reconstruction, with a particular interest in cardiac SPECT imaging. Much of my research has been about improving image quality while preserving details that matter for interpretation.

One problem I've worked on is **where denoising belongs in the reconstruction process**. In our 2024 paper in *EJNMMI Physics*, we studied a convolutional network applied during iterative SPECT reconstruction, rather than only to the final reconstructed image.

### 🔭 Selected work

**Denoising during SPECT reconstruction**  
[Paper — EJNMMI Physics (2024)](https://doi.org/10.1186/s40658-024-00687-3)

The study combined OSEM reconstruction with a two-phase trained denoising network. The reconstruction was implemented in MATLAB, while the neural network was built using TensorFlow and Keras. We evaluated the approach against conventional filtering and post-reconstruction deep denoising.

**2D OSEM reconstruction**  
[MATLAB code](https://github.com/FYousefzadeh/in-house-simple-OSEM2D-code)

A simple 2D OSEM implementation referenced in the paper above.

### ✨ Areas I work with

- Deep learning for image processing, including CNNs and GANs
- Medical image reconstruction and denoising
- TensorFlow, Keras, Python, and MATLAB
- Image-quality evaluation and experimental comparison

### 🌱 Currently exploring

I'm also spending time on reproducible model workflows and the tools used to move models beyond research experiments, including ONNX and Docker.

### 🔗 Research profile

[Publications and researcher profile (ORCID)](https://orcid.org/0009-0006-2976-7709)
