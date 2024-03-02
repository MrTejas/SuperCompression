# SuperCompression
A python library for image compression using Machine Learning

## Models
There are currently 4 different SR models supported in the module. They can all upscale images by a scale of 2, 3 and 4. LapSRN can even upscale by a factor of 8. They differ in accuracy, size and speed.

- EDSR [1]. This is the best performing model. However, it is also the biggest model and therefor has the biggest file size and slowest inference. You can download it [here](https://github.com/Saafke/EDSR_Tensorflow/tree/master/models).
- ESPCN [2]. This is a small model with fast and good inference. It can do real-time video upscaling (depending on image size). You can download it [here](https://github.com/fannymonori/TF-ESPCN/tree/master/export).
- FSRCNN [3]. This is also small model with fast and accurate inference. Can also do real-time video upscaling. You can download it [here](https://github.com/Saafke/FSRCNN_Tensorflow/tree/master/models).
- LapSRN [4]. This is a medium sized model that can upscale by a factor as high as 8. You can download it [here](https://github.com/fannymonori/TF-LapSRN/tree/master/export).


## References
* [1] Bee Lim, Sanghyun Son, Heewon Kim, Seungjun Nah, and Kyoung Mu Lee, “Enhanced Deep Residual Networks for Single Image Super-Resolution”, 2nd NTIRE: New Trends in Image Restoration and Enhancement workshop and challenge on image super-resolution in conjunction with CVPR 2017.

* [2] Shi, W., Caballero, J., Huszár, F., Totz, J., Aitken, A., Bishop, R., Rueckert, D. and Wang, Z., “Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network”, Proceedings of the IEEE conference on computer vision and pattern recognition CVPR 2016.

* [3] Chao Dong, Chen Change Loy, Xiaoou Tang. “Accelerating the Super-Resolution Convolutional Neural Network”, in Proceedings of European Conference on Computer Vision ECCV 2016.

* [4] Lai, W. S., Huang, J. B., Ahuja, N., and Yang, M. H., “Deep laplacian pyramid networks for fast and accurate super-resolution”, In Proceedings of the IEEE conference on computer vision and pattern recognition CVPR 2017.

## Article Links

1. [Deep Learning based Super Resolution with OpenCV](https://towardsdatascience.com/deep-learning-based-super-resolution-with-opencv-4fd736678066)