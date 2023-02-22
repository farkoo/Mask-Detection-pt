# Mask Detection

In this project, we are going to determine from the image of people's faces whether the person is wearing a mask or not using PyTorch.

## 1. Training Different Models
Initial weighting using methods:
1. Kaiming
2. Xeviar

I used AlexNet network architecture as the main basis for building different networks.
You can see the list of various models that I have taught below:
* No Dropout and No Batch Normalization
  - Adam Optimizer
  - SGD Optimizer
  - RMSProp Optimizer
* Dropout and No Batch Normalization
  - SGD Optimizer
* Dropout and Batch Normalization
  - SGD Optimizer

## 2. Using WandB to find the best configurations for hyperparameters
Obtaining optimal values for hyperparameters in deep neural networks using wandb
<p align=center>
  <img src="https://github.com/farkoo/Mask-Detection-pt/blob/master/wandb.png">
</p>


## 3. Evaluation of the best model using real images
In this section, to evaluate the performance of the best model on unseen data, I downloaded 10 images with a mask and 10 images without a mask. Then, using opencv, the area of the person's face is extracted, the dimensions of the image are changed to 32 x 32. Then the images are given one by one to the best model and finally the accuracy of the model performance is obtained.


## 4. Transfer Learning
At the end, we fine tune the Resnet50 pretrained model on our data and use it to classify the unseen data.


## Support

**Contact me @:**

e-mail:

* farzanehkoohestani2000@gmail.com

Telegram id:

* [@farzaneh_koohestani](https://t.me/farzaneh_koohestani)

## License
[MIT](https://github.com/farkoo/Mask-Detection-pt/blob/master/LICENSE)
&#0169; 
[Farzaneh Koohestani](https://github.com/farkoo)
