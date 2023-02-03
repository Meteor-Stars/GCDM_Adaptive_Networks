# GCDM_Adaptive_Networks
This repository contains the official implementation for the paper "Collaborative Decision Making for Adaptive Deep Networks"
## Introduction
This paper has increased the accuracy of all popular adaptive networks and also increased the accuracy of state-of-the-art improved techniques for them by presenting three methods to make full use of classifiers located in different depths of the adaptive networks. First, the Collaborative Decision Making (CDM) module is proposed to integrate the good knowledge of the early classifiers into late classifiers based on evidence fusion theory. Second, for enhancing the quality of the CDM module, we have improved the current evidence fusion method by introducing the effective balance term to it. Finally, we propose the Guided Collaborative Decision Making (GCDM) module, in which the CDM module works based on regularized training. Our methods won't bring extra computational costs and negative effects on the original model.
### Methods Overview
<img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/methods_overview_comparsion.jpg" width="550"><img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/bugdeted_classification_difference.jpg" width="300">

### Difference comparison and Process for using our methods
<img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/model_used_process.jpg" width="500">

### Anytime prediction results on CIFAR-100, Mini-ImageNet and ImageNet
<img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/anytime_Cifar100.png" width="300"><img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/anytime_MiNi_ImageNet.png" width="300"><img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/anytime_ImageNet.png" width="300">

### Budgetd batch classification results on CIFAR-100, Mini-ImageNet and ImageNet
<img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/dynamic_cifar100.png" width="300"> <img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/dynamic_MiNi_ImageNet.png" width="300"> <img src="https://github.com/Meteor-Stars/GCDM_Adaptive_Networks/blob/master/Figures/dynamic_ImageNet.png" width="300"> 
