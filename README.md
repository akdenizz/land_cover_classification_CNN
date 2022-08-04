# Land Cover Classification with CNN on MATLAB

## About Dataset

Dataset has six categories. These categories are shown in the image below:
* barren land
* building
* grassland
* road
* trees
* water

![Visible Spectrum of Categories](/classes.jpg "SAT-6 Dataset Classes")


> Each image has four channels. The first three channels are red, green and blue. 
The fourth channel is near infrared (NIR), which primarily captures vegetation.

Each image is size 28-by-28 pixels. For a pretrained network such as AlexNet 
to classify these images, you would have to substantially resize them. You 
would also have to remove the fourth channel, since AlexNet only accepts 
images with three channels.

To perform transfer learning with this data set, you would substantially increase 
the training time and you would lose valuable information about your images.

>Instead of transfer learning, you can train network from scratch. In this project you will classify images with your own CNN. 

![Visible and Near-Infrared Spectrum](/sat_img.png "SAT-6 Dataset")

You can find the dataset [here!](http://csc.lsu.edu/~saikat/deepsat/)

or you can find it in the project files as ***satData.mat*** !

>🚀🌟 To see how perform the project run the ***land_cover_classification_from_scratch.mlx*** livescript. 