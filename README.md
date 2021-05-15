# MSE-Net

## Introduction
Medical image segmentation plays an important role in auxiliary diagnosis in clinical application.  In the diagnosis and treatment of ischemic stroke, in order to help clinicians carry out rapid diagnosis and treatment, deep learning method is needed to quickly identify and accurately segment the lesion area in the case image.  In order to enhance the detection effect of the model on multi-scale, we design a deep learning network Multi-Encoder-Unet which can effectively fuse multi-scale feature information. The network is composed of ASPP-Unet and Residual encoder. ASPP-Unet is an encoding-decoding structure combined with an empty space convolution pooling pyramid ( ASPP ) structure. The auxiliary network is used to extract the depth features of the detected image. Multi-Encoder-Unet uses multi-scale feature fusion strategy to effectively enhance the detection ability of the lesion area.  We divide the pathological images into four levels according to the number of pixels in the mask region, and test the proposed combination methods on ATLAS dataset.  We compared the algorithm with three latest methods ( D-UNet, X-Net, and Double-UNet ).   The results show that our method performs best in all performance indexes, and achieves the best quality performance in DSC = 0.6405 and accuracy = 0.6388.

## Dataset
Our experiments all conducted on ATLAS database, which is available at [http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)

## Network
![image](https://user-images.githubusercontent.com/46143477/118352396-cf705e80-b593-11eb-90a0-a50d30a714b7.png)

## Example
![image](https://user-images.githubusercontent.com/46143477/118352510-6dfcbf80-b594-11eb-8c0e-aca31330e90d.png)

## Experiment
