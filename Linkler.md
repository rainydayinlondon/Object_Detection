# Object_Detection
Faster R-CNN  https://lilianweng.github.io/lil-log/2017/12/31/object-recognition-for-dummies-part-3.html

https://towardsdatascience.com/faster-rcnn-object-detection-f865e5ed7fc4#:~:text=Faster%20RCNN%20is%20an%20object,SSD%20(%20Single%20Shot%20Detector).


FASTER RCNN Makale'ye ekleyebileceğin linkler : (Faster RCNN Yapısı ile igili.)
https://dongjk.github.io/code/object+detection/keras/2018/05/21/Faster_R-CNN_step_by_step,_Part_I.html
https://tryolabs.com/blog/2018/01/18/faster-r-cnn-down-the-rabbit-hole-of-modern-object-detection/


Object_Detection&amp;Classification

https://towardsdatascience.com/how-to-get-a-job-in-ai-with-no-experience-16526874165d

https://franky07724-57962.medium.com/using-keras-pre-trained-models-for-feature-extraction-in-image-clustering-a142c6cdf5b1


https://learnopencv.com/keras-tutorial-transfer-learning-using-pre-trained-models/


TENSORBOARD GRAFİKLER
https://stackoverflow.com/questions/48111847/tensorflow-object-detection-api-what-do-the-losses-mean-in-the-object-detectio


https://luminoth.readthedocs.io/en/latest/tutorial/04-visualizing-the-training-process.html

The losses for the Region Proposal Network:

Loss/RPNLoss/localization_loss/mul_1: Localization Loss or the Loss of the Bounding Box regressor for the RPN

Loss/RPNLoss/objectness_loss/mul_1: Loss of the Classifier that classifies if a bounding box is an object of interest or background

The losses for the Final Classifier:

Loss/BoxClassifierLoss/classification_loss/mul_1: Loss for the classification of detected objects into various classes: Cat, Dog, Airplane etc

Loss/BoxClassifierLoss/localization_loss/mul_1: Localization Loss or the Loss of the Bounding Box regressor
