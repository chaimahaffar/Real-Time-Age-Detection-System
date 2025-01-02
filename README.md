<h1>Real-Time Age Detection System</h1>

<h2>Description</h2>
This project involves the creation of a real-time system capable of estimating the age of individuals from facial images or video feeds. The system analyzes facial features to provide an accurate age estimation. The solution is designed for integration into applications such as demographic analysis, personalized marketing, and security systems.  
<br />

<h2>Technologies Used</h2>
- <b>Deep Learning</b> (Convolutional Neural Networks)  
- <b>VGG16</b> (Pre-trained model for feature extraction and transfer learning)  
- <b>OpenCV</b> (for face detection and preprocessing)  
- <b>PyTorch</b> (for model fine-tuning and inference)  

<h2>Environments Used</h2>
- <b>Python</b>  
- <b>Google Colab</b> (for training and testing)  

<h2>Project Workflow</h2>

<h3>1. Data Preparation</h3>
<p>
 The dataset is preprocessed to normalize the images, ensuring consistency in size, scale, and brightness. The data is split into training, validation, and testing sets.
</p>

<h3>2. Model Training</h3>
<p>
The system uses **VGG16**, a pre-trained convolutional neural network, as the backbone. The model is fine-tuned on the dataset to predict the age of individuals. By leveraging transfer learning, the training time is significantly reduced while achieving high accuracy. Training involves multiple epochs with hyperparameter tuning to maximize performance and minimize loss.
</p>

<h3>3. Real-Time Detection and Age Estimation</h3>
<p>
The fine-tuned VGG16 model is deployed for real-time inference. Using **OpenCV**, faces are detected from live video feeds or static images, and the model estimates the age of each detected face. The system is capable of processing multiple faces simultaneously, making it robust for various applications.
</p>


<h2>Results</h2>
<p>
The final system demonstrates high accuracy in age estimation across various age groups. Below is an example of the real-time system in action:
</p>

<p align="center">
  Real-Time Age Detection in Action: <br/>
  <img src="https://i.imgur.com/AQfu0c4.jpeg" height="60%" width="60%" alt="Real-Time Age Detection"/><br />
</p>
