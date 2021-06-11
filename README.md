# This is the offical repository of the paper: [CNN Based Non Contact Detection of Food Level in Bottles from RGB Images](https://par.nsf.gov/servlets/purl/10094310) 
Authors: Yijun Jiang, Elim Schenck, Spencer Kranz, Sean Banerjee, and Natasha Kholgade Banerjee

---
<img width="900" alt="level_detection_architecture" src="https://user-images.githubusercontent.com/46984040/121624237-2b1cf300-ca3f-11eb-9c7a-597dd7dcf35f.png">

# Abstract 
In this paper, we present an approach that detects the level of food in store-bought containers using deep convolutional neural networks (CNNs) trained on RGB images captured using an off-the-shelf camera. Our approach addresses three challenges—the diversity in container geometry, the large variations in shapes and appearances of labels on store-bought containers, and the variability in color of container contents—by augmenting the data used to train the CNNs using printed labels with synthetic textures attached to the training bottles, interchanging the contents of the bottles of the training containers, and randomly altering the intensities of blocks of pixels in the labels and at the bottle borders. Our approach provides an average level detection accuracy of 92.4% using leave-one-out cross-validation on 10 store-bought bottles of varying geometries, label appearances, label shapes, and content colors.

---
