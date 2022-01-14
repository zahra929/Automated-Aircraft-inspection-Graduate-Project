### __Computer Vision graduate project__

In this work, we used U-Net architecture to automatically detect aircraft dents. U-Net is a convolutional network architecture used for fast and accurate image segmentation. It is symmetric in the form of a U, which consists of a contraction path (down sampling) to capture the context and a symmetrical up sampling path that allows precise localization.
We tried to improve and evaluate prediction performance of this model by applying different techniques: 

-Using conventional data augmentation technique flipping, rotation and clipping to improve the models performances and testing GAN’s performance in data augmentation with small dataset.
-Using a Pre-trained VGG-16 model with ImageNet Dataset as a backbone of U-NET:
-Exploring various modified U-Net architecture such as Attention U-Net and TransU-Net which uses a hybrid CNN-Transformer structure to use detailed high-resolution spatial information from CNN functionality and the global context encoded by Transformer (ViT).
- Explore the effect of data augmentation on every architecture 

__About Files__ :

For each model there is two versions :   
    -The first trained without data augmentation  
    -The second one was augmented using a selected combination of augmentations techniques  

The file Data augmentation contains the code applying the augmentation techniques.

__References__:

[1] Anil Dogru, Soufiane Bouarfa, Ridwan Arizar, and Reyhan Aydo (2020) “Using convolutional neural Networks to automate aircraft maintenance visual inspection” 

[2] Bouarfa, S., Doğru, A., Arizar, R., Aydoğan, R., & Serafico, J. (2020). Towards automated aircraft maintenance inspection. A use case of detecting aircraft dents using mask r-cnn. In AIAA Scitech 2020 Forum [AIAA 2020-0389] (AIAA Scitech 2020 Forum; Vol. 1 Part). American Institute of Aeronautics and Astronautics Inc. (AIAA). https://doi.org/10.2514/6.2020-0389

[3] Olaf Ronneberger, Philipp Fischer, and Thomas Brox (2015), “U-Net: Convolutional Networks for Biomedical Image Segmentation” available at: https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28

[4]Ozan Oktay, Jo Schlemper, Loic Le Folgoc, Matthew Lee, Mattias Heinrich, Kazunari -- Misawa, Kensaku Mori, Steven McDonagh, Nils Y Hammerla, Bernhard Kainz, Ben Glocker, Daniel Rueckert (2018), ‘’ Attention U-Net: Learning Where to Look for the Pancreas’' Available at : https://openreview.net/pdf?id=Skft7cijM

[5] Jieneng Chen, Yongyi Lu, Qihang Yu, Xiangde Luo, Ehsan Adeli, Yan Wang, Le Lu, Alan L. Yuille, Yuyin Zhou (2021) “TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation” Available at: https://arxiv.org/abs/2102.04306

