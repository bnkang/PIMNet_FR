## PIMNet_FR
Created by [Bong-Nam Kang](https://sites.google.com/view/bnkang/home) and [Daijin Kim](http://imlab.postech.ac.kr/members_d.htm) at [POSTECH IM Lab](http://imlab.postech.ac.kr)

Porject page: [https://sites.google.com/view/bnkang/research/face-recognition-using-deep-neural-networks]

### Overview
We propose a new face verification method that uses multiple deep convolutional neural networks (DCNNs) and a deep ensemble, that extracts two types of low dimensional but discriminative and high-level abstracted features from each DCNN, then combines them as a descriptor for face verification. Our DCNNs are built from stacked multi-scale convolutional layer blocks to present multi-scale abstraction. To train our DCNNs, we use different resolutions of triplets that consist of reference images, positive images, and negative images, and triplet-based loss function that maximize the ratio of distances between negative pairs and positive pairs and minimize the absolute distances between positive face images. A deep ensemble is generated from features extracted by each DCNN, and used as a descriptor to train the joint Bayesian learning and its transfer learning method. On the LFW, although we use only 198,018 images and only four different types of networks, the proposed method with the joint Bayesian learning and its transfer learning method achieved 98.33% accuracy. In addition to further increase the accuracy, we combine the proposed method and high dimensional LBP based joint Bayesian method, and achieved 99.08% accuracy on the LFW. Therefore, the proposed method helps to improve the accuracy of face verification when training data is insufficient to train DCNNs.

### Citation

If you're using this code in a publication, please cite our papers.
     
  @INPROCEEDINGS{8014823, 
    author={B. N. Kang and Y. Kim and D. Kim}, 
    booktitle={2017 IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)}, 
    title={Deep Convolutional Neural Network Using Triplets of Faces, Deep Ensemble, and Score-Level Fusion for Face Recognition}, 
    year={2017}, 
    pages={611-618}, 
    doi={10.1109/CVPRW.2017.89}, 
    month={July}
  }

### Licence

This software is for research purpose only.
Check LICENSE file for details.
