Dog Image Processor
This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).
-- Project Status: [Completed]

Installation

Using a browser, navigate to https://colab.research.google.com/. From there, upload the ipynb files to run our training jupyter notebooks.

In the dogs_resnet_cnn.ipynb file, change the paths for the drive directory to your drive path. This way you will be able to save the models to your drive directory for later evaluation in the code. The dogs.ipynb file requires no additional tuning to run.
  
Project Intro/Objective
The main purpose of this project is to be able to identify dogs by their breeds. By doing so, we will be able to improve at home camera processing to ensure we know what is entering our home, whether its not a dog, or a breed different from our own - we could then program the door by which dogs enter to refuse entry. By doing so we can add another layer of safety to home security and feel safer knowing it is our fluffy friends entering our home, and not an intruder.


Partner(s)/Contributor(s)  
⦁	Will Kencel, Brian Johnson, Victor Hsu
⦁	wkencel@sandiego.edu, bjohnson2@sandiego.edu, vhsu@sandiego.edu

Methods Used
⦁	Computer Vision
⦁	Machine Learning
⦁	Deep Learning

Technologies
⦁	Python
⦁	Tensorflow
⦁	MatPlot (graphing libraries)
⦁	scikit-learn libraries (evaluation of models)
⦁	Keras (high lvl API used with tensorflow)

Project Description

Data source: https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set - A dataset with a large number of dog breed images
Number of Variables: 7946 train images + 700 test images + 700 validation images (9346 total images) in 224x224x3 jpg format.
Size of the Dataset: 9346 total images. ~ 225 MB to download. There is also a dictionary of the data available at the kaggle link (dogs.csv)

We wanted to explore different types of training to ensure we could pick the best one for our modeling. We tried two pre-trained models, VGG and RESNET50, and one out of the box CNN model. We also explored adjusting parameters for the pre-trained models, and performed preprocessing on the images prior to training. We wanted to know if we could have a model that performed well for our task of identifying dogs. 

To perform evaluation, we generated data from the sklearn library, in particular confusion matrix and classification report to show how the models would perform for each breed of dog and overall accuracy. Looking at the data, VGG model had the best performance overall for each breed with CNN performing second best. Resnet 50 had the most issues in evaluation step which if we had more time, we would explore with additional adjustments to hyperparameters, datasets, etc. The better performance of the VGG model can be attributed to the ResNet50 and CNN models overfitting as the complexity of those models may not have been suited to dog breed classiciation task which inherently has a smaller dataset.

We encountered some minor roadblocks in processing the dataset/initial setup, but after we reached training step it was more smooth. Colab was an important tool in terms of resources for training which helped to speed along training/evaluation.

License

CC0: Public Domain
https://creativecommons.org/publicdomain/zero/1.0/

Acknowledgments
Thanks to the professor for teaching us, and to the team who worked hard on this project.
