# MSE-Net

## Introduction
Medical image segmentation plays a critical role in auxiliary diagnosis in clinical application. That being said, accurately segment the lesion area from the case image is still a challenging task, since the size and the shape of lesions are always different. Exploiting contexts from multi-scale features is believed to be valuable for tackling these challenges in medical image. In this paper, we proposed a novel multiple encoders network for stroke lesion segmentation, called MSE-Net, which is main composed of ASFF module and Residual encoder. Specifically, ASFF uses the parallel architecture of atrous convolutions with different sampling rates to obtain the context information on multi-scale features. Residual encoder obtains the high-level semantic features with the high-resolution. Furthermore, MSE-Net uses the encoding-decoding framework. We divide the pathological images into three levels according to the number of pixels in the mask region, and test the proposed combination methods on ATLAS dataset. The experimental results show that the proposed MSE-Net has better performance in DSC = 0.6405 and accuracy = 0.6388 than state-of-the-art methods such as D-UNet, X-Net, and Double-UNet. The source code of our method is available at https://github.com/jcfszxc/MSE-Net.

As shown in our GitHub, we released our model first, and the rest will follow. The model of which is available on BaiduYun.

Link: [https://pan.baidu.com/s/166NPd-LHtZr_e9W2FTc7jw ](https://pan.baidu.com/s/166NPd-LHtZr_e9W2FTc7jw )
Code: jcfs 

## Dataset
Our experiments all conducted on ATLAS database, which is available at [http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)

## Network
![image](https://user-images.githubusercontent.com/46143477/118392107-5abc2380-b66a-11eb-816d-2e0e50463a84.png)

## Example
![image](https://user-images.githubusercontent.com/46143477/118352510-6dfcbf80-b594-11eb-8c0e-aca31330e90d.png)

## Experiment
![image](https://user-images.githubusercontent.com/46143477/118392120-7293a780-b66a-11eb-96d5-05b1388ac7c4.png)

