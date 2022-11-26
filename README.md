# Transfer-Learning-using-AlexNet-for-Car-Make-and-Model

The development of a computer vision application that can recognize a certain vehicle model from an image is an intriguing and difficult subject to solve. The difficulty with this issue is that different car models can often look remarkably similar, and the same vehicle can sometimes look different and difficult to identify depending on lighting, angle, and many other variables. To create a model that can recognize a specific vehicle model for this project, I choose to train a convolutional neural network (CNN) known as AlexNet using Fast ai and PyTorch.


Figure depicts Transfer Learning by Alexnet. (Lu, Lu and Zhang, 2019) :

![ALTL](https://user-images.githubusercontent.com/94075388/204095550-64faf72d-bf92-4385-a237-0bca4bc5efe0.jpg)


<img width="451" alt="AlexNet" src="https://user-images.githubusercontent.com/94075388/204095634-250d1604-eeaa-45aa-bdfa-a6173d033f88.png">


# Dataset

For the Dataset: https://ai.stanford.edu/~jkrause/cars/car_dataset.html

There are 16,185 photos of 196 different kinds of cars in the Cars collection. The data has been divided into 8,144 training photos and 8,041 testing images, roughly splitting each class 50-50. Classes are usually given in the Make, Model, and Years categories.

Visualising the Dataset:

![VGG16-DATA](https://user-images.githubusercontent.com/94075388/204095620-836f2563-5856-4c87-ae62-bf045ada92e9.png)

# Results

Accuracy obtained: 88% 

![AlexNet_fastai_plot](https://user-images.githubusercontent.com/94075388/204097003-9342d0c4-1260-4646-833f-495a9b9f2d3c.png)

