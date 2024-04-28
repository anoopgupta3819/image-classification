image-classification 

==========================================================================================
Image Classification with Convolutional Neural Networks (CNN): Develop a CNN model to classify images in a dataset, such as the CIFAR-10 or ImageNet dataset, and explore techniques for model optimization and performance improvement.

CIFAR-10-C OR CIFAR-10-P both dataset download to ref this link https://zenodo.org/records/2535967#.XncuG5P7TUJ

Facebook AI Research mixup-cifar10 ref this link https://github.com/facebookresearch/mixup-cifar10?tab=readme-ov-file



========================================================================================================================================
Optimized primitives for inter-GPU communication. ref this link https://github.com/NVIDIA/nccl
Improved-Regularization-of-Convolutional-Neural-Networks Deep learning has been increasingly used in recent years, leading to state-of-the-art performance on different tasks, including object detection [1], semantic segmentation [2], image captioning [3], etc. Most of this success can be attributed to the use of convolutional neural networks (CNNs) [4] that are capable of learning complex hierarchical feature representation of images. The complexity of the tasks given to the deep neural network has increased over time, leading to advanced architectures that require a high computational complexity. These models usually contain tens to hundreds of millions of parameters that are needed for solving a task. However, the greater number of parameters in a network would lead to a higher chance of overfitting, which would then lead to a weak generalizability.

In order to combat overfitting during the training process, researchers have introduced regularization techniques. Regularization techniques incorporate changes into the model in order to reduce the generalization error without harming the training error. A performance improvement can be expected if the regularization technique is chosen carefully. Commonly regularization techniques include dataset augmentation, layer dropout, and weight penalty regularization (L1- or L2-based). Each technique uses a different approach to increase generalizability of the model. Recently, several novel regularization techniques have been introduced to further combat the overfitting issue in large-sized models. In this study, we aim to evaluate the effectiveness of three novel augmentation techniques, namely cutout regularization [5], mixup regularization [6], and self-supervised rotation predictor [7], [8]. The following section discusses the related work.



![image](https://github.com/anoopgupta3819/image-classification/assets/115916305/578e949e-0a2b-4450-ba1e-ead8dbca57f1)
