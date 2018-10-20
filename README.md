# Computer Vision - Style Transfer
I worked on this project with the Statistical Modeling and Deep Learning Lab in Undergraduate Lab at Berkeley.  

Using PyTorch, we deployed a VGG convolutional neural network to identify objects in images. We then synthesized a texture from a Van Gogh artwork while preserving the content of our base image.

# Original Images
Content Image:
![Alt text](Images/Tuebingen_Neckarfront.jpg)

Style Image:
![Alt text](Images/vangogh_starry_night.jpg)

# Visualization / Results
After running style_transfer.py on our images, we can see our minimization of loss with each iteration of of our model.  Running numerous iterations of our model produced the content below.

![Alt text](Images/loss.png)
![Alt text](Images/style_transfer_output.png)
