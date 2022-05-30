## Face Emotion Recognition

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

The model gave an accuracy of 0.68 on the test data which was kept aside. This indicates the model is generalizing well on unseen data as well. Here are some results of the real time test. Since the observations for disgust class were pretty low, the model is able to correctly recognize rest of the classes pretty well.
![emotion detection output  pic](https://user-images.githubusercontent.com/101975292/170924695-741bef85-0f6d-40a5-8381-80ca476d5394.png)
![emotion detection output pic 2](https://user-images.githubusercontent.com/101975292/170924706-5aa254e9-9867-434f-85aa-2cd3370454ba.png)


# 4.Evaluation Metrics

Loss and Accuracy Graph![accuracy](https://user-images.githubusercontent.com/101975292/170873156-bcb74c15-3b66-410c-99cb-6ec92f9986e1.png)

# 5.Execution Instructions

1.Create a project folder
2.Create a virtual environment, for windows:
conda create -n deep learning python=3.9.12
activate deep learning
3.Download localapp.py, model(1).h5 and haarcascade_frontalface_default.xml in the same folder.
4.Install the dependencies from requirements.txt
Note: Install opencv-python as well, opencv-python-headless in the requirements file is to adjust the size requirements for web app deployment purposes. To run app.py requirements.txt is enough.
5.Run real_time_demo.py

# 6.Web Application Deployment

Streamlit : https://share.streamlit.io/rupasawant95/face-emotion-recognition/main/localapp.py

# 7. Conclusion

    We trained the neural network and we achieved the highest validation accuracy of 63.43%.
    Pre Trained Model didn't gave appropriate result.
    Our Model can succesfully detect face and predict emotion on live video feed as well as on an image.


