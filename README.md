# Densely-Connected-Neural-Network-in-Object-Detection

Train a machine learning model effective in object detection which could be used in assisitng thoese who are visually impaired in our community. 

## Motivation
### Visual Impaired Satistics
As of 2018, The WHO (World Health Organization) estimated that there are approximately 1.3 billion people around the globe who live with some form of vision impairment. Of those, approximately 285 million are completely blind, and 90% of them live in a developing country. Therefore many visually impaired citizens around the globe do not have access, nor the financial support to afford assistive technology.

![alt text](https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwj26-O_ypniAhVSTt8KHbREBHkQjRx6BAgBEAU&url=https%3A%2F%2Fwww.augsburg.edu%2Fclass%2Fgroves%2Fassistive-technology%2Feveryone%2F&psig=AOvVaw3HiMs2B7vb3rdro4uqUbbX&ust=1557873854351360)

### Assistive Technology
Assistive technology Assistive technology is an umbrella term covering the systems and services related to the delivery of assistive products and services. Some of the most common blind assistive technology are blind assisting headphones such as Jabra Assist, screen readers, and braille printers. However, currently, most assistive technology focuses on enhancing the users' other senses such as touch and hearing to replace the vision.

## Our Project

### Machine Learning Model
Our implementation focuses on using our knowledge in machine learning and computer science to develop a classification algorithm that could help visually impaired citizens in our community. We did so through training a machine learning model which could view and classify objects through images. Densely Connected Neural Network(DenseNet) is a machine learning architecture inspired by CNN(Convolutional Neural Networks). Different from CNN, DenseNet concatenates layers of output to make sure components of inputs are connected. In doing so, intuitively speaking, DenseNets optimize their own operation layers in addition to optimizing output and thus become more and more efficient as training happens. We choose to use DenseNet as our primary machine learning model to implement as it can deal with large data inputs without vanishing gradient and static learning rate phenomenons. In addition, we also compared the model to previous models of CNN and ResNet on the same dataset, to test this claim.

### Dataset
We decided to use CIFAR100 as our dataset. CIFAR 100 is the state-of-the-art object image dataset; furthermore, the dataset is easily incorporated across both tensorflow and pytorch, and thus allowed us to compare our model performance to other forms of neural networks. During our project brainstorming session, we also looked into other datasets such as Malaria Infected Cell, and Grand Challenge Datasets. However, due to hardware limitations, we were unable to train datasets larger than 1.5 GB, as it would significantly impact performance and training speed of our model.
