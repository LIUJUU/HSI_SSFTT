# PyTorch Demo of the Hyperspectral Image Classification method - SSFTT.

Using the code should cite the following papers:

L. Sun, G. Zhao, Y. Zheng, Z. Wu. "Spectral–spatial feature tokenization transformer for hyperspectral image classification." IEEE Transactions on Geoscience and Remote Sensing. DOI:10.1109/TGRS.2022.3144158.

Feel free to contact us if there is anything we can help. Thanks for your support!

cs_zhaogr@nuist.edu.cn 

# Description.

In hyperspectral image (HSI) classification, each pixel sample is assigned to a land-cover category. In the recent past, convolutional neural network (CNN)-based HSI classification methods have greatly improved performance due to their superior ability to represent features. However, these methods have limited ability to obtain deep semantic features, and as the layer’s number increases, computational costs rise significantly. The transformer framework can represent highlevel semantic features well. In this article, a spectral–spatial feature tokenization transformer (SSFTT) method is proposed to capture spectral–spatial features and high-level semantic features. First, a spectral–spatial feature extraction module is built to extract low-level features. This module is composed of a 3-D convolution layer and a 2-D convolution layer, which are used to extract the shallow spectral and spatial features. Second, a Gaussian weighted feature tokenizer is introduced for features transformation. Third, the transformed features are input into the transformer encoder module for feature representation and learning. Finally, a linear layer is used to identify the first learnable token to obtain the sample label. Using three standard datasets, experimental analysis confirms that the computation time is less than other deep learning methods and the performance of the classification outperforms several current state-of-the-art methods.
