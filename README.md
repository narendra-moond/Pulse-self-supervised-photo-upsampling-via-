**Launch in Google Colab:**
-  [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/ctawong/PULSE_from_image_url/blob/master/PULSE_URL.ipynb)

# PULSE from image URL
Take an image URL as input, this Colab notebook first crop and produce a low-resolution face image, and invoke PULSE algorithm to produce a high resolution image, so that you can compare how well it does.

![example](https://github.com/ctawong/PULSE_from_image_url/blob/master/jackieChan.PNG)

Based on "PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models" repository. 



![example](https://github.com/ctawong/PULSE_from_image_url/raw/master/transformation.gif)

Given a low-resolution input image, Face Depixelizer searches the outputs of a generative model (here, [StyleGAN](https://github.com/NVlabs/stylegan)) for high-resolution images that are perceptually realistic and downscale correctly.



**Based on:** [Face-Depixelizer](https://github.com/tg-bomze/Face-Depixelizer)
**Based on:** [PULSE](https://github.com/adamian98/pulse)

**Article**: [PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models](https://arxiv.org/abs/2003.03808)

