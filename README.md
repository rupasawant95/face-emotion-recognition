# 1. Convolutional Neural Netwroks
A Convolutional Neural Network is a Deep Learning technique that can take an input image and assign weights and biases to various objects in the image, allowing it to distinguish between them. In comparison to other classification algorithms, ConvNet requires substantially less pre-processing. While basic approaches require hand-engineering filters, ConvNets can learn these features with enough training.

![1653830947668](https://user-images.githubusercontent.com/101975292/170871376-fab6830e-d9c6-43d7-bee9-b6d7e2407caf.jpg)

The convolutional layer is the most important component of a CNN because it is where the majority of the computation takes place. It requires input data, a filter, and a feature map, among other things. A feature detector, also known as a kernel or a filter, will traverse across the image's receptive fields, checking for the presence of the feature. Convolution is the term for this procedure.

Pooling Layer reduces the number of parameters in the input by performing dimensionality reduction. The pooling process sweeps a filter across the entire input, similar to the convolutional layer, however this filter does not have any weights. Instead, the kernel uses an aggregation function to populate the output array from the values in the receptive field.

Each node in the output layer, on the other hand, connects directly to a node in the previous layer in the fully-connected layer. This layer performs classification tasks based on the features retrieved by the previous layers and their various filters. While convolutional and pooling layers typically utilize ReLu functions to categorize inputs, FC layers typically use a softmax activation function to provide a probability from 0 to 1. 

# 1. face-emotion-recognition
Facial emotion recognition is the process of detecting human emotions from facial expressions. The human brain recognizes emotions automatically, and software has now been developed that can recognize emotions as well. This technology is becoming more accurate all the time, and will eventually be able to read emotions as well as our brains do.  AI can detect emotions by learning what each facial expression means and applying that knowledge to the new information presented to it. Emotional artificial intelligence, or emotion AI, is a technology that is capable of reading, imitating, interpreting, and responding to human facial expressions and emotions.

# 2. Face Emotion Recognition Model

Facial expression recognition system is a computer-based technology and therefore, it uses algorithms to instantaneously detect faces, code facial expressions, and recognize emotional states. It does this by analyzing faces in images or video through computer powered cameras embedded in laptops, mobile phones, and digital signage systems, or cameras that are mounted onto computer screens. Facial analysis through computer powered cameras generally follows three steps:

A. Face detection

Locating faces in the scene, in an image or video footage.

B. Facial Feature Detection

Extracting information about facial features from detected faces. For example, detecting the shape of facial components or describing the texture of the skin in a facial area.

C. Facial expression and emotion Classification

Analyzing the movement of facial features and/or changes in the appearance of facial features and classifying this information into expression-interpretative categories such as facial muscle activations like smile or frown; emotion categories happiness or anger; attitude categories like (dis)liking or ambivalence

# 3. Real Time Emotion Detection Results

The model gave an accuracy of 0.68 on the test data which was kept aside. This indicates the model is generalizing well on unseen data as well. Here are some results of the real time test. Since the observations for disgust class were pretty low, the model is able to correctly recognize rest of the classes pretty well.![1653832693512](https://user-images.githubusercontent.com/101975292/170872919-1f2459ae-f75f-4cf2-89df-d359a5ef7be7.png)
