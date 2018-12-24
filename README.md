## Face_Pytorch
The implementation of  popular face recognition algorithms in pytorch framework, including arcface, cosface and sphereface and so on.

All codes are evaluated on Pytorch 0.4.0, Ubuntu 16.04.10, CUDA 9.1 and CUDNN 7.1.


### Train with CASIA-WebFace

Model Type   |    Loss Type   |  LFW Acc.  |  AgeDB-30  |  CFP-FP  
-------------|:--------------:|-----------:|-----------:|---------:
MobileFaceNet|     ArcFace    |    99.21%  |            |
LResNet-50   |     ArcFace    |            |            |   
LResNet-101  |     ArcFace    |            |            |     



### Train with VGGFace2
Model Type   |    Loss Type   |  LFW Acc.  |  AgeDB-30  |  CFP-FP  
-------------|:--------------:|-----------:|-----------:|---------:
MobileFaceNet|     ArcFace    |            |            |
LResNet-50   |     ArcFace    |            |            |   
LResNet-101  |     ArcFace    |            |            |     


### Train with MS-Celeb-1M
Model Type   |    Loss Type   |  LFW Acc.  |  AgeDB-30  |  CFP-FP  
-------------|:--------------:|-----------:|-----------:|---------:
MobileFaceNet|     ArcFace    |            |            |
LResNet-50   |     ArcFace    |            |            |   
LResNet-101  |     ArcFace    |            |            |     




### References
[CosFace_pytorch](https://github.com/MuggleWang/CosFace_pytorch)  
[MobileFaceNet_Pytorch](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)