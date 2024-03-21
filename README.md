

# Image Super Resolution
## Motivation for the Project
This is a project done under IET NITK where the goal is to enhance the brightness of low light image and then pass it to the super resolution model to enhance the visibility and clarity of the image and removing the noise such that the output image is much more clear and visibily pleasing and aesthetically appealing.
### Description

Our proposed model begins by implementing a mechanism to determine whether the input image exhibits characteristics of low-light conditions.Causes of low-light conditions can be due to insufficient or
absent light source or uneven illumination caused by back-light and shadows. Subsequently, we will develop a function capable of discerning whether the given image meets the criteria for low-light classification. Upon identification of a low-light image, we will employ the Zero DCE model to enhance its brightness.

Following the enhancement process through the Zero DCE model, the image will undergo further refinement using the Super Resolution model. This subsequent step aims to produce a substantially clearer and denoised version of the image, leveraging the sophisticated capabilities inherent to the Super Resolution model.

In essence, our model is designed to automatically detect and address low-light scenarios in images, enhance their brightness using Zero DCE, and further refine them to achieve superior clarity and noise reduction through the Super Resolution model. This holistic approach ensures that images exhibiting low-light conditions are effectively processed to yield optimal visual outcomes.
#### Working

The Zero-Reference Deep Curve Estimation (Zero DCE) model is a state-of-the-art method in the field of image enhancement, particularly in addressing low-light conditions. Unlike traditional methods that rely on reference images or prior knowledge, the Zero DCE model operates without any reference input, hence the term "zero-reference."

At its core, the Zero DCE model utilizes deep neural networks to predict a transformation curve that can effectively enhance the brightness and visibility of low-light images. This transformation curve is learned directly from the input low-light image itself, without the need for additional reference images or external information.

The key innovation of the Zero DCE model lies in its ability to capture and exploit the inherent characteristics of low-light images to generate accurate and effective enhancement curves. By leveraging deep learning techniques, the model can adaptively adjust the brightness levels of pixels in the input image, effectively amplifying details and enhancing visibility without introducing excessive noise or artifacts.

The Super Resolution Generative Adversarial Network (SR-GAN) represents a cutting-edge approach to image enhancement, specifically targeted at increasing the resolution and fidelity of low-resolution images. Leveraging the power of Generative Adversarial Networks (GANs), SR-GAN operates on the principle of adversarial training, where two neural networks, namely the generator and the discriminator, engage in a competitive learning process to produce high-quality, high-resolution images.

The generator network within SR-GAN is tasked with learning a mapping function that takes a low-resolution image as input and generates a corresponding high-resolution output. Through an iterative process, the generator learns to upscale the image while preserving important details and features. Concurrently, the discriminator network is trained to distinguish between real high-resolution images and those generated by the generator. This adversarial setup encourages the generator to produce increasingly realistic and visually pleasing results.

One of the key strengths of SR-GAN lies in its ability to generate photo-realistic images with enhanced resolution, surpassing the capabilities of traditional interpolation-based methods. By harnessing the power of GANs, SR-GAN is able to produce sharp, detailed, and visually appealing images that closely resemble their high-resolution counterparts.


## Links

[link text](https://li-chongyi.github.io/Proj_Zero-DCE.html)

[link with title](https://pyimagesearch.com/2022/06/06/super-resolution-generative-adversarial-networks-srgan/)









