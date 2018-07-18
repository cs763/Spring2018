<h1>Computer Vision (CS 763) - Spring 2018 Project Information</h1>
You can choose projects given in the list below or you can propose your project and get it approved by the TAs.
<h2>Timeline</h2>
<ul>
  <li>Project Proposal Submission: 19/01/2018
  <li>Proposal Review: 22/01/2018
  <li>Mid Term Review: 09/03/2018
</ul>

<h2>Project Proposal Form</h2>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSfGj--GVldmIWVZFAisMirPZEE6S3a1cEYjTHsiNXm__GPpFg/viewform">Project Proposal Form</a>

<h2>Some Proposed Projects</h2>
<ol>
<li><a href=https://github.com/mehtanihar/mask-rcnn><b>MASK R-CNN for Object Instance Segmentation </b></a><br>
  <i>Meet Pragnesh Shah, Mehta Nihar Nikhil, Parth Ashit Kothari   </i><br>
  
  Mask R-CNN efficiently detects objects in an image while simultaneously generating a high-quality segmentation mask for each instance. Instance segmentation involves detection of all objects in the image as well as precise segmentation of each instance.The related research paper was published by Facebook AI Research. Through this project, we aim to implement this model in pytorch and perform experiments on the PASCAL-VOC dataset. We also shall make an attempt to provide a modification to the model which helps in improving the accuracies on the vision tasks as described in the paper. Another incentive of this project is that no working code is yet available in pytorch/tensorflow, which are the popular frameworks today. This will largely benefit the deep learning community.

<li><a href=https://github.com/pmkalshetti/object_detection><b>Object Detection</b></a> <br>
   <i> Kratika Gupta, Pratik Kalshetty, Naman Rastogi   </i><br>
  
  The aim of this project is to implement a system which is capable of detecting and localising objects in an image. The goal is to achieve accurate object detection at a high speed. The ideas in YOLO (You Only Look Once: Unified, Real-Time Object Detection) will help in implementing the project. For the purpose of this project, the publicly available PASCAL VOC dataset will be used. It consists of $10$k annotated images with $20$ object classes with $25$k object annotations.

<li><a href=https://github.com/Tejesh-Raut/Computer-Vision-Augmented-Reality><b>Plane Extraction on Surfaces</b></a> 
  <br>  <i> Tejesh Raut, Deep Modh, Chaitanya Rajesh   </i><br>   
  
  In this project, we aim to track a section of a plane in the image so that a user can place a 3D object on the surface, for augmented reality applications. We would recognise if the texture to be detected is present or not in the image. If present, we can then find its position and orientation in the image and finally pply the transformation on predefined hardcoded 3D model in order to place the object on the surface plane. The output will be an image along with the 3D model placed on it.
  
<li><a href=https://github.com/udion/pose2action><b>Activity Recognition</b></a> 
  <br>   <i>Naman Jain, Sahil Shah, Uddeshya   </i><br>

In our project, we plan to work on detecting human activities from videos. There exists a good amount of literature and data in this area, yet, there is room for improvement. Our initial endeavours would be towards exploring 3D CNNs, as is proposed in the literature, to approach the problem. We also intend to incorporate Connectionist Temporal Classification (CTC) losses in our temporal architectures for improved detection.

<li><p><a href=https://github.com/mohit-madan/glyph-AR><b>Glyph based AR application</b></a>
  <br>   <i>Sachin Goyal, Mohit Madan, Michelle Barnette  </i><br> 

We wish to perform glyph based AR using the following steps: 1) Glyph-boundary recognition using edge detection. 2) Estimating of the distortion (orientation and scaling) in 3D space. 3) Placing any image on the glyph in 3D space (applying rigid transformations). 4) Identification of the glyph pattern and placing specific image on glyph. 5) (If time permits) placing a 3D object on glyph.

<li><a href=https://github.com/bhatsukanya/Number-Plate-Detection-and-Recognition><b>Vehicle registration plate detection and recognition</b></a> 
  <br><i>Chintan Tundia, Shabana K M, Sukanya Bhattacharjee </i><br>

In this project, we aim to build an automated pipeline to perform license plate detection from images of vehicles and perform recognition of characters in the number plate. This would involve first localizing the number plate in the image followed by detecting the numbers. For the current project, we plan to stick to Indian number plates only.
                                        
<li><a href=https://github.com/alokwhitewolf/Video-frame-prediction-by-multi-scale-GAN> <b> Video Prediction using GANS </b></a> 
  <br><i>Alok Kumar Bishoyi </i><br>

Adversarial networks have recently been used to predict future video frames. I plan to implement ‘Deep Multi-Scale Video Prediction beyond Mean Square Error’ for Chainer users. I also plan to test and train on sample games like Pong, Breakout, etc.

<li> <a href=https://github.com/arijitx/Amazon-Satelite-Image-Labeling><b> Label satellite image chips from Amazon rainforest with atmospheric conditions and various classes of land cover </b></a> <br>
<i>Kalpesh Dusane, Arijit Mukherjee, Vaishali Shakya </i><br>

It is crucial to identify the terrain of Amazon rainforest to help the government track the region of deforestation or human infiltration of forest which in turns help minimize the devastating effects of climate change. Due to recent advancements in technology, we can capture satellite images but manually monitor and labeling this satellite images would be a tedious and unreliable task. To solve this problem, we represent model which assign multiple labels to the image describing various climate conditions and landmark. We seek to explore different deep convolutional neural network architectures to do the image labeling task and learn how changing various factors such as hyperparameters affect the performance of our neural net model.

<li><a href=https://github.com/Manojkilaru/CVProject><b>Style Transfer on Car Exteriors</b></a><br>
<i>Uday Kusupati, Jayanth Shankar, Manoj Kilaru </i><br>
Applying style from another image(painting, texture etc) to image of car, sort of similar to prisma but for car exteriors.
  
Idea is to identify the body of car using segmentation on the car parts. Next we will build upon an efficient solution proposed by Leon A. Gatys where they train feed-forward convolutional neural networks by defining and optimizing perceptual loss functions. Intent is to also use cues like depth, neighborhood pixels, as well as planarity to transfer style better.

<li><a href=https://github.com/AbhishekKumar16/CV_Project><b>Implementing Re3: Real-Time Recurrent Regression Networks for Visual Tracking of Generic Objects</b></a><br>
<i>Rishab Garg, Abhishek Kumar </i><br>

Implementing <a href="https://arxiv.org/abs/1705.06368">Re3: Real-Time Recurrent Regression Networks for Visual Tracking of Generic Objects</a>

A robust object tracking algorithm based which utilises the combination of CNN & LSTM. This optimized tracker is capable of tracking objects at 150 FPS, while attaining impressive results on various benchmarks. This tracker also handles temporary occlusion better than other comparable trackers. Involving LSTM gives real-time deep object tracker capability to incorporating temporal information into its model. All this is achieved in with a single forward pass.

<li><a href=https://github.com/SeeTheC/Face-Detection-using-Faster-R-CNN><b>Face detection using CNN</b></a><br>
  <i> Khursheed Ali, Ayush Goyal and Anshul Gupta
 </i> <br>  

Face detection has vas applications in the areas ranging from surveillance, 
security, crowd size estimation to social networking etc. The challenge 
lies in creating a model which is agnostic to lightning conditions, 
pose, accessories and occlusion. We aim to create a pipeline which takes 
an image as an input and creates a bounding box on the faces of all the 
people in the image. Further, if the dimension of the face is above a certain 
threshold, we will detect the expression of the person.

<li><a href=https://github.com/yudi09/pytorch-image-captioning><b>Image Captioning</b></a><br>
  <i>Yugal Sachdev</i><br>

The goal of this project is to generate natural language descriptions of images and their regions. It will use combination of CNN over image regions, bidirectional RNN over sentences, and a structured loss function that aligns the two modalities - text and images, through a multimodal embedding. I will be implementing 'Deep Visual-Semantic Alignments for Generating Image Descriptions' on Flikr8K, Flickr30K and MSCOCO datasets using Tensorflow and Keras.
</ol>
