

|Name   | Paper  |  Code   | Year | Contribution |
|---|---|---|---|---|
| EfficientDet | [link](https://arxiv.org/abs/1911.09070) | [link](https://github.com/google/automl/tree/master/efficientdet) | 2020 | propose a weighted bi-directional feature pyramid network (BiFPN); consistently achieve much better efficiency than prior art across a wide spectrum of resource constraints |
| ChamNet | [link](http://openaccess.thecvf.com/content_CVPR_2019/papers/Dai_ChamNet_Towards_Efficient_Network_Design_Through_Platform-Aware_Model_Adaptation_CVPR_2019_paper.pdf) | [link](https://github.com/facebookresearch/mobile-vision) | 2019 | leverage existing efficient network building blocks and focuses on exploiting hardware traits and adapting computation resources to fit target latency and/or energy constraints. [CNN Latency Look-up Table](https://github.com/facebookresearch/mobile-vision/tree/master/runtime_lut) |
| FBNet | [link](http://openaccess.thecvf.com/content_CVPR_2019/html/Wu_FBNet_Hardware-Aware_Efficient_ConvNet_Design_via_Differentiable_Neural_Architecture_Search_CVPR_2019_paper.html) | [link](https://github.com/facebookresearch/mobile-vision) | 2019 | propose a differentiable neural architecture search (DNAS) framework that uses gradient-based methods to optimize ConvNet architectures, avoiding enumerating and training individual architectures separately as in previous methods. |
| EfficientNet | [link](https://arxiv.org/abs/1905.11946) | [link](https://github.com/lukemelas/EfficientNet-PyTorch) | 2019 | uniformly scales all dimensions of depth/width/resolution using a simple yet highly effective compound coefficient; use neural architecture search to design a new baseline network and scale it up to obtain a family of models |
| MixNet | [link](https://bmvc2019.org/wp-content/uploads/papers/0583-paper.pdf) | [link](https://github.com/romulus0914/MixNet-PyTorch) | 2019 | mix up multiple kernel sizes in a single convolution |
| SENet | [link](http://openaccess.thecvf.com/content_cvpr_2018/html/Hu_Squeeze-and-Excitation_Networks_CVPR_2018_paper.html) | [link](https://github.com/moskomule/senet.pytorch) | 2019 | adaptively recalibrate channel-wise feature responses by explicitly modelling interdependencies between channels; produce significant performance improvements for existing state-of-the-art deep architectures at minimal additional computational cost |
| CondenseNet | [link](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_CondenseNet_An_Efficient_CVPR_2018_paper.pdf) | [link](https://github.com/ShichenLiu/CondenseNet) | 2018 | It combines dense connectivity with a novel module called learned group convolution. |
| ESPNet | [link](http://openaccess.thecvf.com/content_ECCV_2018/papers/Sachin_Mehta_ESPNet_Efficient_Spatial_ECCV_2018_paper.pdf) | [link](https://sacmehta.github.io/ESPNet/) | 2018 | it is based on a new convolutional module, efficient spatial pyramid (ESP), which is efficient in terms of computation, memory, and power. ESPNet is 22 times faster (on a standard GPU) and 180 times smaller than the state-of-the-art semantic segmentation network PSPNet, while its category-wise accuracy is only 8% less. |
| MobileNetV2 | [link](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sandler_MobileNetV2_Inverted_Residuals_CVPR_2018_paper.pdf) | [link](https://pytorch.org/hub/pytorch_vision_mobilenet_v2/) | 2018 | a novel layer module: the inverted residual with linear bottleneck. This module takes as an input a low-dimensional compressed representation which is first expanded to high dimension and filtered with a lightweight depthwise convolution. Features are subsequently projected back to a low-dimensional representation with a linear convolution |
| ShuffleNetv2 | [link](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ningning_Light-weight_CNN_Architecture_ECCV_2018_paper.pdf) | [link](https://pytorch.org/hub/pytorch_vision_shufflenet_v2/) | 2018 | evaluate the direct metric on the target platform, beyond only considering FLOPs; derive several practical guidelines for efficient network design; a new architecture is presented |
|ShuffleNet | [link](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_ShuffleNet_An_Extremely_CVPR_2018_paper.html) | [link](https://github.com/kuangliu/pytorch-cifar/blob/master/models/shufflenet.py) | 2018 | utilize two new operations, pointwise group convolution and channel shuffle, to greatly reduce computation cost while maintaining accuracy |
| MobileNet | [link](https://arxiv.org/abs/1704.04861) | [link](https://github.com/pytorch/vision/blob/master/torchvision/models/mobilenet.py) | 2017 | uses depthwise separable convolutions to build light weight deep neural network |
| DenseNet | [link](https://arxiv.org/pdf/1608.06993.pdf) | [link](https://github.com/liuzhuang13/DenseNet) | 2017 | reuse feature map from multiple layers |
| SqueezeDet | [link](https://arxiv.org/abs/1612.01051) | [link](https://github.com/QiuJueqin/SqueezeDet-PyTorch) | 2016 | In our network, we use convolutional layers not only to extract feature maps but also as the output layer to compute bounding boxes and class probabilities. The detection pipeline of our model only contains a single forward pass of a neural network, thus it is extremely fast. |
|GoogleNet    | [link](http://openaccess.thecvf.com/content_cvpr_2015/html/Szegedy_Going_Deeper_With_2015_CVPR_paper.html) | [link](https://pytorch.org/hub/pytorch_vision_googlenet/)  |2015   | increase the depth and width of the network while keeping the computational budget constant;separable filters;1x1 convolutions to reduce number of weights and multiplications |
| VGG | [link](https://arxiv.org/pdf/1409.1556.pdf) | [link](https://github.com/pytorch/vision/blob/master/torchvision/models/vgg.py) | 2015 | a thorough evaluation of networks of increasing depth using an architecture with very small ( 3 × 3) convolution filters |

