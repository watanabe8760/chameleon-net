# Chameleon Net
This is an experiment of deep neural network by TensorFlow.  
The idea of Chameleon Net is pretty simple, yet I've never seen: applying [Image Style Transfer CNN](http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html) repeatedly from different style images so that one content picutre changes its style one after another continuously. To implement the idea, I tweaked a trick in the part of loss function and optimization in training process. The deep neural network used in this experiment is [VGG 16-layer model](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) which had been pre-trained. 
Also, this is the final project of [Creative Applications of Deep Learning with TensorFlow](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info). So I used some of utility functions that the course provided, specifically to aid visual presentation in the jupyter notebook. Those utility functions are stored under `libs`.

![alt tag](https://raw.githubusercontent.com/watanabe8760/chameleon-net/master/output/chameleon.gif)

This time I used my selfie as a content picture (I thought I might be able to produce "cool me"), but the idea of chameleon net, how to handle loss function and optimization is applicable to any content image. Let's style a image in a chameleon manner!
