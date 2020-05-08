# Densenet_121_Kerv2D


This repo contains the code for a Kervolutional implementation of Densenet 121 for images of size 512x512 . Kervolutional neural networks proposed by Chen Wang et.al show a marked improvement in performance over standard CNNs in image feature extraction as the various kernels itself incorporate non-linearity unlike a CNN which does this only through the ReLU activation which leads to much lower efficiency in feature extraction . Here we present a Kervolutional implementation of the popular Densenet 121 framework specifically geared towards 512x512 images .

Many applications such as Medical Imaging , Genomics and even Facial Recognition require high resolution images of size 512x512 or 1024x1024 , most pretrained networks however atmost are geared towards sizes of 256x256 not only that the efficiency of CNNs itself is quite disputable for images at these resolutions we shall present here comparsions between vanilla Densent 121 adapted for this resolution and the new Kerv_Densent_121 adapted for this resolution .

Initial results for resized Imagenet are as follows :

![Non linearity v/s convergence](https://github.com/rsn870/Densenet_121_Kerv2D/blob/master/images/nonlinearvsconv.png?raw=true)


![Kernels v/s Convergence](https://github.com/rsn870/Densenet_121_Kerv2D/blob/master/images/kernelsvsconv.png?raw=true)


![Hyperparameters v/s Convergence](https://github.com/rsn870/Densenet_121_Kerv2D/blob/master/images/hypervsconv.png?raw=true)
