### DSSN_release
This repository is a Pytorch implementation of the paper [**"Deep Spectral-Spatial Network for Single Image Deblurring"**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9094296)

Seokjae Lim, Jin Kim and [Wonjun Kim](https://sites.google.com/site/kudcvlab)  
IEEE Signal Processing Letters (Early Access)

When using this code in your research, please cite the following paper:  

Seokjae Lim, Jin Kim and Wonjun Kim, **"Deep Spectral-Spatial Network for Single Image Deblurring,"** **IEEE Signal Processing Letters (Early Access)**.

### Model architecture
![examples](./examples/network.png)

### Experimental results with state-of-the art methods on the GOPRO dataset
![examples](./examples/results1.png)
Several results of single image deblurring. First row : input blurry images selected from the GOPRO dataset. Second row : deblurring results by Tao et al. Third row : deblurring result by Zhang et al. Fourth row : deblurring results by the proposed method. Note that blurred regions (red and yellow-colored rectangles) are enlarged for better view. Best views in colors.

### Experimental results with state-of-the art methods on the Köhler dataset
![examples](./examples/results2.PNG)
Several results of single image deblurring. First column : input blurry images selected from the Köhler dataset. Second column : deblurring results by Nah et al. Third column : deblurring result by Zhang et al. Fourth column : deblurring results by the proposed method. Note that all experiments are conducted with parameters, which are trained based on the GOPRO dataset, without any modification.

### Requirements

* Python >= 3.5
* Pytorch 0.4.0
* Ubuntu 16.04
* CUDA 8 (if CUDA available)
* cuDNN (if CUDA available)
