# Real_Time_Video_Dehazing

Image and video haze removal has been a challenging problem due to its ill-posed nature. Real-life scenarios like outdoor photography/videography, computer vision tasks, and more severe cases like visibility while driving (where human lives are at stake) often suffer from bad weather conditions. The observed objects lose visibility and contrast due to atmospheric haze, fog, rain, snow, and smoke.

In this project, we implemented an existing method for real-time video dehazing based on a novel color attenuation prior, which was first tested to dehaze single images and later implemented on videos due to its astonishing results. We can estimate the depth information using a depth map, extract the screen object transmission, and estimate the global atmospheric light.

To prevent blocking artifacts due to pixelation, we refine the depth map using a guided filter to smoothen the image. Finally, we can restore the haze-free frame by inversing the haze imaging model. The whole process can quickly be implemented on modern GPUs for real-time performance. Experimental results demonstrate the effectiveness and robustness of the proposed framework by outperforming the state-of-the-art approaches in terms of time complexity and visual quality.

We offer to implement this framework with the help of Raspberry Pi or NVIDIA Jetson system for real-life applications such as car security systems, outdoor surveillance, remote sensing, and intelligent vehicles.

## Tangible output:
An application based on the video dehazing model and implement it on Raspberry Pi or NVIDIA Jetson for real-time applications and demonstration purposes.
