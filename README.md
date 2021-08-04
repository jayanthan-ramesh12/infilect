# infilect - Object detection problem

The given problem statement is to create an object detection model that can detect the items in a shelf in a super market and give predictions on the same. The model I chose for this purpose is SSD resnet 50 retinanet 640x640 . This model uses resnet 50 to create the feature map and the retinanet architacture to produce the object detection. The other models I considered for this purpose are SSD mobilenet and SSD resnet 101 retinanet. The reason for choosing this model is that it is not constrained like the mobilenet but also uses less memory compared to SSD resnet 101. If this model did not give good acceptable result I would have chosen SSD resnet 101. 

The project includes:
* shop_tfrecord.ipynb - To generate the tf record for training and testing record
* shop_training.ipynb - training code for SSD resnet 50 Model
* shop_prediction.ipynb - To give predictions of the model
* shop_evaluation - gives the evaluation metrics of the model
* image2products.json - product count in each image
* metrics.json - evaluation metrics of test dataset

# Getting started

The code is developed using google colab and google drive as the storage. Please ensure there is atleast 10 GB storage available in the google drive for processing.


