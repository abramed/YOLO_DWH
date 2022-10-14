# YOLO_DWH


In this project, we have addressed the problem of object detection optimization for real-time
applications without the use of specific hardware (GPU). To this end, we have proposed and
experimented with several optimisation approaches and techniques. First, we focused on the
size of the input data in the architecture and the different transformations performed during

its passage through the convolution network. Also, we reviewed the way of defining the convo-
lution filters by experimenting with several possible configurations of the convolution blocks.

Finally, we used convolution layers for data reduction instead of maximum pooling layers, which
improved the accuracy and maintained an excellent detection speed. Thus, these experiments
allowed us to design our deep learning architecture, optimised for object detection in GPU-free

environments, which we evaluated on four datasets : Pascal Voc, MS COCO, Vehicule OpenI-
mage and Mask Wearing. We concluded this project by comparing the results obtained by our

architecture with other existing object detection methods.

You can see in this figure the full architecture that we came with [fcn8.pdf](https://github.com/abramed/YOLO_DWH/files/9786951/fcn8.pdf)

You will find in the repository the configuration file of our final architecture and the weight of our model.
You will also find a small python script that gonna help you to launch it.

You can also see some comparaison with the state of the art of Object detection right there : 
![MS COCO](https://user-images.githubusercontent.com/46135758/195865421-87fab1d4-265c-4165-ae19-caacb8ce122d.PNG)


![VOC](https://user-images.githubusercontent.com/46135758/195865516-0fcc9920-ead7-456e-bb8d-5522770c56ef.PNG)
