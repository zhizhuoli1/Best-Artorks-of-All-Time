# Deep Learning Project - Best Artorks of All Time

## Project Objectives:
1. Predict the artist and the style of an artwork through convolutional neural network
2. Transform the style of a random image to the style of an assigned artwork
3. Detect the objects in an artwork

## Team Members 
Zhizhuo Li
Angela Zheng
Yuming Liao
Huaxuan Wang

## 1. Data Preparation
<img width="1016" alt="Screen Shot 2021-10-24 at 10 16 33 PM" src="https://user-images.githubusercontent.com/77072543/138629666-cb6ce85a-b5d5-4405-9e2f-5ba4154bc9f5.png">

## 2. Artist Prediction
#### We used four pre-trained models to predict the artist, including ResNet50, VGG19, Inception and EfficientNet.
1. ResNet50 - Micro-architecture modules & 50 weighted layers & global average pooling  
2. VGG19 - Stacked 3x3 convolutional layers for increasing depths & 19 weighted layers & fully-connected layers
3. Inception - Multi-level feature extractor & Smaller architecture than both VGG and ResNet
4. EfficientNet - Effective compound scaling method for increasing the model size & Reduced the parameters and FLOPS (Floating Point Operations Per Second) manifold

### Model Evaluation for Predictions
<img width="1018" alt="Screen Shot 2021-10-24 at 10 21 07 PM" src="https://user-images.githubusercontent.com/77072543/138629961-2ecf0c7d-a1ef-46bf-995f-de0215c6eaa4.png">

## 3. Style Transformation 
### We used pre-trained VGG19 models to extract the content representation and style representation, and then apply them into new arts.
1. Results with different train steps
<img width="983" alt="Screen Shot 2021-10-24 at 10 22 54 PM" src="https://user-images.githubusercontent.com/77072543/138630150-45a30688-273b-41a3-ad30-292d3944e73c.png">

2. Resutls with different styles
<img width="1056" alt="Screen Shot 2021-10-24 at 10 23 00 PM" src="https://user-images.githubusercontent.com/77072543/138630165-4b2a77c2-5e0a-4c23-a590-406548e6b941.png">

## 4. Object Detection
### YOLO v4 model is used to detect the common objects
<img width="324" alt="image" src="https://user-images.githubusercontent.com/77072543/138630241-7a468315-7e71-4337-8ac2-ad6211e43c79.png">
<img width="324" alt="image" src="https://user-images.githubusercontent.com/77072543/138630252-a082aa13-1eb6-4b2a-87da-be3acf5fad08.png">


