Dog Image Processor
This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).
-- Project Status: [Completed]

Installation

Using a browser, navigate to https://colab.research.google.com/. From there, upload the ipynb files to run our training jupyter notebooks.

In the dogs_resnet_cnn.ipynb file, change the paths for the drive directory to your drive path. This way you will be able to save the models to your drive directory for later evaluation in the code.
  
Project Intro/Objective
The main purpose of this project is to be able to identify dogs by their breeds. By doing so, we will be able to improve at home camera processing to ensure we know what is entering our home, whether its not a dog, or a breed different from our own. By doing so we can add another layer of safety to home security and feel safer knowing where our fluffy friends are.


Partner(s)/Contributor(s)  
⦁	Will Kencel, Brian Johnson, Victor Hsu
⦁	wkencel@sandiego.edu, bjohnson2@sandiego.edu, vhsu@sandiego.edu

Methods Used
⦁	Computer Vision
⦁	Machine Learning
⦁	Deep Learning

Technologies
⦁	Python
⦁	Tensorflow libraries


Project Description

Data source: https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set - A dataset with a large number of dog breed images
Number of Variables: 7946 train images + 700 test images + 700 validation images (9346 total images) in 224x224x3 jpg format.
Size of the Dataset: 9346 total images. ~ 225 MB to download. There is also a dictionary of the data available at the kaggle link (dogs.csv)

We wanted to explore different types of training to ensure we could pick the best one for our modeling. We tried two pre-trained models, VGG and RESNET50, and one out of the box CNN model. We also explored adjusting parameters for the pre-trained models, and performed preprocessing on the images prior to training. We wanted to know if we could have a model that performed well for our task of identifying dogs. 

[add evaluation, data analysis etc. discussion here; any roadblocks, challenges, etc.]

License

CC0: Public Domain
https://creativecommons.org/publicdomain/zero/1.0/

Acknowledgments
Thanks to the professor for teaching us, and to the team who worked hard on this project.
