# Convolutional neural network prediction algorithm 
## Software: TensorFlow, matplotlib

## Work description and analysis:
§ Description of the work:
The goal is to achieve the maximum level of accuracy of the program so that the substituted images are guessed correctly. For this experiment, the dataset with pictures of tomatoes and apples was used (https://www.kaggle.com/datasets/samuelcortinhas/apples- or-tomatoes-image-classification).

§ Data preparation for the training:
The used dataset consists of two sets of images (tomatoes 43 images and apples 54 images).

§ Neural networks training
For achieving the best results, the algorithm goes through 5 convolutional layers and then trains using TensorFlow.

§ Relevant metrics for the case(s):
The accuracy rate varies for each ‘epoch’ but in the end, the algorithm predicts all images perfectly.
      
## To sum up
 For the used dataset, the algorithm works with the highest rate of accuracy, and at all times the program was tested, there was no single image predicted wrongly.
In my opinion, the project is done successfully because the algorithm was also tested with another set of images (https://www.kaggle.com/datasets/deepcontractor/is-that-santa- image-classification), it defined whether it is a Santa Claus in the image or not, and the result was highly accurate as well.

## How to download and make it work on your laptop?

The algorithm is universal for different images and can recognize/compare only two sets of imagies.

To start, you need to download the file and create a new folder with images inside the directory with the main file.

In the code, the name of the folder i used is called "data", so if you wish to change the name, you need to correct the code in two places.


```
20 data_dir = 'data' # set the folder with the imagies
```

```
38 data_direct = tf.keras.utils.image_dataset_from_directory('data') # set the folder with the imagies
```
