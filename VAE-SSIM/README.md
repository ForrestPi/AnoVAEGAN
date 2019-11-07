# Variational Autoencoder(PyTorch)
Variational Autoencoder for face image generation implemented with PyTorch, Trained over a combination of CelebA datasets.

The loss function can divided to two fold:
KL_loss and reconstruction loss.

1） KL_loss 用于约束隐特征的分布；
2） 重构损失用于保证重构的图像和原始图像内容尽可能一致

常用的重构损失是L2 loss，保证重构图像的每个像素服从高斯分布
本仓库代码用于研究SSIM作重构损失函数时生成图像的效果

## Results
Original Faces vs. Reconstructed Faces:
### Group (1)
![img](imgs/img1.jpg)
![rec](imgs/rec1.jpg)
### Group (2)
![img](imgs/img2.jpg)
![rec](imgs/rec2.jpg)
### Group (3)
![img](imgs/img3.jpg)
![rec](imgs/rec3.jpg)
