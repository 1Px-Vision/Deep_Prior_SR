# Deep Prior SR

![Journal_DIP](https://github.com/1Px-Vision/Deep_Prior_SR/blob/main/Journal_DIP.jpg)
Single-pixel imaging (SPI) has become an innovative approach for computational imaging, particularly beneficial in environments where traditional imaging systems fall short. SPI shines in low light conditions and 
without high-quality cameras for specific spectral ranges. It uses structured light to convert one-dimensional signals into detailed two- and three-dimensional images. The fidelity of SPI-generated images 
largely depends on the amount of temporal measurements taken. Deep learning enhances the reconstruction of SPI images but needs more training data, especially for specific spectral bands. In our study, we introduce a novel  method that integrates the Deep Image Prior technique with Generative Adversarial Networks (GANs) to improve SPI image quality in the near-infrared (NIR) spectrum  (850 to 1550 nm). This approach bypasses the need for extensive SPI image datasets by adopting an unsupervised method for image super-resolution rooted in Deep Image Prior.  We assess different neural  network models, including UNet and GAN frameworks, to gauge their performance in enhancing SPI-based computational vision systems.

![DIP](https://github.com/1Px-Vision/Deep_Prior_SR/blob/main/Simulate_DIP.jpg)

## The Challenge of SPI Resolution

SPI reconstructs images from a series of intensity measurements using a single photodetector. While this method offers advantages in low-light and specialized spectral ranges, it suffers from resolution limitations due to the inherent under-sampling of spatial information. Traditional deep learning-based super-resolution techniques require extensive labeled datasets, which are difficult to acquire for SPI in NIR bands. Our proposed approach mitigates this limitation by utilizing an unsupervised learning framework.

![DIP_result](https://github.com/1Px-Vision/Deep_Prior_SR/blob/main/Result_DIP.jpg)
## Hybrid Approach: DIP Meets GAN

Deep Image Prior (DIP) is a compelling technique that reconstructs high-quality images without requiring a large training dataset. By coupling DIP with a Generative Adversarial Network (GAN), we improve SPI resolution through an unsupervised learning paradigm. This approach offers several advantages:

* **Reduced Data Dependency:** Unlike supervised methods, DIP leverages image priors, reducing the need for extensive SPI datasets.

* **Enhanced Super-Resolution:** The GAN component learns to refine the image quality, making it more detailed and perceptually accurate.

* **Optimized Neural Architectures:** We enhance the performance by leveraging variations of UNet and GAN architectures across four different neural network configurations.

## Future Perspectives

Our results demonstrate that combining DIP with GANs is a promising direction for SPI super-resolution, particularly for niche applications in biomedical imaging, remote sensing, and defense technology. Future research could explore:

* Real-time implementations for SPI-based imaging systems.
* Adaptations to other spectral bands beyond NIR.
* Hybrid models incorporating physics-informed neural networks (PINNs) for further refinement.
