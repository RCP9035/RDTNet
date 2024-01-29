# RDTNet:  Residual Deformable Attention based Transformer Network for Breast Cancer Classification

<p align="justify"> This paper proposes a residual deformable attention based transformer network (RDTNet) for breast cancer 
histopathological image classification. The RDTNet is an end-to-end architecture which is composed of three
key components: a backbone network, a residual deformable transformer layer (RDTL) and a classifier as shown in figure below. </p>
<img src="RDTNet.jpg" alt="Architecture of RDTNet">
<p align="justify"> At first the histopathological image undergoes an initial passage through a backbone CNN network, 
resulting in the extraction of hierarchical feature maps F . Subsequently, these feature maps are fed into the proposed
RDTL to model wide-range feature dependencies. The RDTL introduces a multi-head deformable self-attention (MDSA) module
which leverages the extraction of salient and category-specific features from the crucial regions of the histopathological 
images. In addition, it utilizes skip connections for better feature flow within the network. The resultant feature are finally 
fed to a classification layer to classify the image as benign or malignant. </p>

This repository contains the RDTNet code. Experiments were carried out on widely used publicly available dataset: [BreaKHis](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
