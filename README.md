
<h1>Computer Vision (CS 763) - Spring 2018 </h1>

<h2>Course Information</h2>
<ul>
<li><b>Instructor:</b> <a href="http://www.cse.iitb.ac.in/~ajain/">Arjun Jain</a>
<li><b>Office:</b> 216, CSE New Building
<li><b>Email:</b> <i>ajain@cse DOT iitb DOT ac DOT in</i>
<li><b>Teaching Assistants:</b> Rishabh Dabral, Safeer Afaque
<li><b>Instructor Office Hours (in room 216 CSE New Building):</b> Arjun is on campus only on Thursdays and Fridays. Meet him after class or fix an appointment over email.
</ul>

<h3> Please note that CS663 is a hard prerequisite for this course.</h3> 

<h2>Topics to be covered (tentative)</h2>
<ul>

<li> Camera geometry, camera calibration, vanishing points, important
transformations, homographies
<li> Image registration: RANSAC for point-matching, SIFT overview
<li> Deep Learning in computer vision: the data-driven paradigm, feed
forwards networks, back-propagation and chain rule; CNNs and their
building blocks, generative adverserial networks (GANs)
<li> Deep Learning applications including face detection, CNN
compression, siamese and triplet networks and applications to face
recognition
<li> Algorithms for: shape from shading, optical flow,
Kanade-Lucas-Tomasi algorithm, applications of optical flow
<li> Photometric stereo - deriving shape from multiple images of an
object taken under different lighting conditions; applications to
illumination invariant face recognition, face relighting
<li> Stereo (geometric binocular): epipolar geometry and fundamental
matrix, the correspondence problem and shape from stereo; structure
from motion
</ul>

<h2>Learning materials and textbooks</h2>
<ul>
<li> Lecture slides that will be regularly posted
<li><a href="http://szeliski.org/Book/">Computer Vision: Algorithms and Applications</a>, by Richard Szeliski</li>
<li><a href="http://crcv.ucf.edu/gauss/BOOK.PDF">Fundamentals of Computer Vision</a>, by Mubarak Shah</li>
<li> <a href = "http://www.deeplearningbook.org/">Deep Learning</a>, by Ian Goodfellow and Yoshua Bengio and Aaron Courville 
<li> All <a href="https://github.com/facebook/iTorch">iTorch</a> notebooks for topics covered in class can be found <a href="https://github.com/cs763-dl/2017Spring/tree/master/Notebooks">here</a>
</ul>

<h2>Grading Policy</h2>
<ul>
	<li> Mid-sem exam: 20%
	<li>Final exam (cumulative): 20%
	<li>Assignments (five or six): 35% (all to be done in groups of 2-3 students)
	<li>Course project: 20% (to be done in the same group of 2-3 students)
	<li>Class participation: 5%
	<li>Course project work will be presented by the student group during a viva at the end of the course. During this viva, each student in the group will be separately questioned, not only on the project work, but also the assignments. Each student is expected to contribute to each and every assignment and the course project. 
	<li>Audit requirements: You must write both exams, submit all assignments and the project, and score at least 40% to get an AU.
</ul>

<h2>Other Policies</h2>
<ul>
	<li> Assignments will be given out (typically) once every two or three weeks. They must be submitted on or before the deadline. No late assignments will be accepted. The programming components of the assignments will typically involve MATLAB and lua, so you must be willing to learn it quickly.
	<li><b>We will adopt a zero-tolerance policy against any forms of plagiarism or any other form of cheating. Just don't do it! In cases of plagiarism, givers and takers will both be considered equally responsible.</b>
	<li>This course is (inherently) cumulative. The syllabus for the final exam will include everything taught during the semester.
</ul>

<h2>Course Projects</h2>

<strong>[02/02/2018] Course projects have now been finalized.</strong>

Go to  <a href="https://github.com/cs763/Spring2018/blob/master/projects/readme.md">this link</a> for the finalized list.
	
<h2>Assignments</h2>
<ul>
    <li><time datetime="2018-01-12">[12-Jan-18]</time> <a href="https://www.dropbox.com/s/mltmtj7bpc401vm/HW1.pdf?dl=0">Assignment 1</a> has been released. The due date for submission is Friday, January 26, 2018.
    <li><time datetime="2018-01-27">[27-Jan-18]</time> <a href="https://www.dropbox.com/s/u0l7gs0dy2rq11l/HW2.pdf?dl=0">Assignment 2 </a> has been released. The due date for submission is Sunday, February 4, 2018.
    <li><time datetime="2018-02-09">[09-Feb-18]</time> <a href="https://www.dropbox.com/s/b92xpq1zvec5956/HW3.pdf?dl=0">Assignment 3 </a> has been released. The due date for submission is Wednesday, February 21, 2018. <strong>Corresponding kaggle competition <a href="https://www.kaggle.com/c/assign3">link</a></strong>
    <li><time datetime="2018-03-06">[06-Mar-18]</time> <a href="https://www.dropbox.com/s/452ubndyxr9x07l/HW4.pdf?dl=0">Assignment 4 </a> has been released. The due date for submission is Monday, March 19, 2018. <strong>Corresponding kaggle competition <a href="https://www.kaggle.com/t/3b06e8618ccd434293ccbabdfe9598d9">link</a></strong>
<li>[2-April-18] <a href ="https://www.dropbox.com/s/cocjql8bfmytxbh/Assignment_5.pdf?dl=0">Assignment 5</a> on Tracking has been <a href="https://www.dropbox.com/s/cocjql8bfmytxbh/Assignment_5.pdf?dl=0">released</a>. Due date: April 2, 2018. <strong>Download the necessary files from <a href="https://www.dropbox.com/s/z3yzd25vgw5cma0/HW5.tar.gz?dl=0">here</a></strong>
</ul>

<h2>Lecture Schedule: </h2>

<table>
  <tbody>  
    <tr>
      <th>Date</th>
      <th>Topics</th>
      <th>Slides</th>
      <th>iTorch Notebooks</th>
      <th>Extra Reading</th>
    </tr>  
    <tr>
      <td>4th Jan. 2018</td>
      <td><ul><li>Introduction to computer vision, applications and course overview <ul></td>
      <td><a href="https://www.dropbox.com/s/6w02e2w4w75xckm/L1.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td align="center">--</td>
    </tr>  
  
   <tr>
      <td>5th Jan. 2018</td>
      <td>
	<strong>Camera Geometry</strong>
	<ul>
	<li>Homogeneous coordinates and projective geometry
        <li>Vanishing points, ideal line, point line duality in P2
        <li>Important 2D and 3D transformations using homogeneous coordinates
        <li>Introduction to the pin-hole camera model
      </ul></td>
      <td><a href="https://www.dropbox.com/s/k70kt7x4ybd2o5b/L1.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td ><a href="http://www.ipb.uni-bonn.de/book-pcv/pdfs/PCV-A-sample-page.pdf">Homogeneous Representations of Points, Lines and Planes</a></td>
  </tr>
     <tr>
      <td>12th Jan. 2018</td>
      <td><ul>
	<li>Modeling the pinhole camera analytically, intinsic and extrinsic parameters
	<li>World, camera, image plane and sensor plane coordinate systems and transformations between them
	<li>Linear and non-linear (lens distortion) errors
	<li>Homography, planar world and pure rotation of the camera
      </ul></td>
      <td><a href="https://www.dropbox.com/s/ezcojdo79iw5aac/L2.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td align="center">--</td>
  </tr>
  </tr>
     <tr>
      <td>13th Jan. 2018</td>
      <td><ul>
	<li>Iterative solutions for dealing with with non-linear (lens distortion) errors
	<li>Normalized,  ideal, euclidian, affine and general camera models
	<li>Orthographic and weak-perspective camera models
	<li>Cross ratios and its applications
	<li>Camera calibration using DLT (known 3D control points)
      </ul></td>
      <td><a href="https://www.dropbox.com/s/laf9ds64739y6wz/L3.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td ><a href="http://inside.mines.edu/~whoff/courses/EENG512/lectures/17-SVD.pdf">Resource on SVD, how/why it can be used to solve eq. sytems of type <strong>Ax=0, |x|=1</strong></a></td>
  </tr>
    </tr>
     <tr>
      <td>18th Jan. 2018</td>
      <td><ul>
	<li>Zhang's camera calibration method, mention of a few DL based calibration methods
	</ul>
	      <strong>Image Alignment</strong>
	<ul>
	<li>Image alignment: problem statement, physically and digitally corresponding points
	<li> Motion models and degrees of freedom; non-rigid/deformable/non-parametric image alignment
	<li> Control point based image alignment using least squares - derivation for pseudo-inverse
	<li> Introduction to the SIFT algorithm
	<li> Forward and reverse image warping - bilinear and nearest-neighbor interpolation
	<li> Mention of DL based image patch descriptors
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/ojghsbe7xgfld0s/L4.pdf?dl=0">Slides(1)</a><br/>
	<a href="https://www.dropbox.com/s/4hcodx1jtdtdnxv/L1.pdf?dl=0">Slides(2)</a>
      </td>
      <td align="center"> -- </td>
      <td align="center"> -- </td>
  </tr>
       <tr>
      <td>19th Jan. 2018</td>
      <td><ul>
	<li>Image alignment using image similarity measures: mean squared error, normalized cross-correlation
	<li>Concept of field of view in image alignment using image similarity measures
	<li>Monomodal and multimodal image alignment
	<li>Concept of joint histograms and behaviour of joint histograms in multi-modal image alignment	
	<li>Concept of entropy and joint entropy, algorithm for multimodal registration by minimizing joint entropy
	<li>Aspects of image registration: 2D/3D, motion model, monomodal or multimodal
	<li>Application scenarios for image alignment: template matching, video stabilization, panorama generation, face recognition, 3D to 2D alignment
	</ul>
	      <strong>Robust Methods in Computer Vision</strong>
	<ul>
	<li>Least squares problems and their relation to the Gaussian distribution on the noise
	<li>Examples of outliers in computer vision
	<li>Explanation of why the Gaussian distribution is unsuited to handling outliers
	<li>Introduction to the Laplacian distribution
	<li>The importance of heavy-tailed distributions in robust statistics
	<li>RANSAC (random sample consensus) algorithm
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/1d5cra9pu6425jz/L2.pdf?dl=0">Slides(1)</a><br/>
	<a href="https://www.dropbox.com/s/xe752gshzpcc3w6/L1.pdf?dl=0">Slides(2)</a>
      </td>
      <td align="center"> -- </td>
      <td align="center"> -- </td>
  </tr>
  
  <tr>
      <td bgcolor="#ffffe6">25th Jan. 2018</td>
      <td>
	      <strong>Recognizing images, objects, scenes (Prof. Suyash P. Awate)</strong>
	<ul>
	<li>Texture modeling and classification
	<li>Image classification, challenges
	<li>Bag of words model, dictionary learning
	<li>Defining image similarity, pyramid match kernel (PMK)
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/tlc40a4bwuqicqo/Recognition.pdf?dl=0">Slides</a><br/>
      </td>
      <td align="center"> -- </td>
      <td align="center"> -- </td>
  </tr>
    <tr>
      <td bgcolor="#ffffe6">1st Feb. 2018</td>
      <td>
	      <strong>Recognizing images, objects, scenes (Prof. Suyash P. Awate)</strong>
	<ul>
	<li>Pyramid match kernel (PMK)
	<li>Kernel coding, local coding, vector quantization, sparse coding, LcLC
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/tlc40a4bwuqicqo/Recognition.pdf?dl=0">Slides</a><br/>
      </td>
      <td align="center"> -- </td>
      <td align="center"> -- </td>
  </tr>
  <tr>
      <td bgcolor="#ffffe6">2nd Feb. 2018</td>
      <td>
	      <strong>Robust Methods in Computer Vision</strong>
	<ul>
	<li>RANSAC: time complexity and expected no. of iterations
	<li>Using RANSAC for Homography estimation
	<li>Introduction to the Laplacian distribution
	<li>Mean versus median: L2 fit versus L1 fit
	<li>LMeds: Least Median of Squares
      </ul>
      <strong>Deep Learning for Computer Vision</strong>
	<ul>
	<li>History, introduction
	<li>Data driven paradigm
	<li>K-NN on CIFAR 10
	<li>Hyperparameters, choice of loss function, cross-validation
      </ul>
      </td>
      <td>
	<a href="https://www.dropbox.com/s/vtieofvop7p02l7/L2.pdf?dl=0">Slides(1)</a><br/>
	<a href="https://www.dropbox.com/s/0905ck0kwdyj6bv/L1.pdf?dl=0">Slides(2)</a><br/>
      </td>
      <td align="center"> <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/NN.ipynb">KNN</a></td>
      <td > <a href="http://parrt.cs.usfca.edu/doc/matrix-calculus/index.html">Matrix calculus reminder</a>
      </td> 
  </tr>
   <tr>
      <td bgcolor="#ffffe6">8th Feb. 2018</td>
      <td>
	<ul>
	<li>Softmax classifier, cross-entropy loss function, regularization
	<li>Optimization: vanilla gradient descent, stochastic gradient descent
	<li>Vanilla momentum, Nesterov momentum, AdaGrad, RMSProp, ADAM 
	<li>Second order optimization methods, it's issues with deep learning
	<li>Good learning rate, learning rate decay
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/fqs0hjisv4o6ukj/L2.pdf?dl=0">Slides</a><br/>
      </td>
      <td align="center"> <a href="https://www.dropbox.com/s/i3jvya22tf5jtbs/GradientCheck.ipynb?dl=0">Gradient Check</a> </td>
      <td > <a href="https://github.com/pytorch/pytorch/blob/master/torch/optim/adam.py#L58">ADAM</a>, 
      <a href="https://github.com/fidlej/optim/raw/master/dok/nesterov_simple.pdf">Nesterov</a> <br/>
      <a href="http://ruder.io/optimizing-gradient-descent/index.html">DL optimization algorithms overview</a>
      </td>
  </tr>
     <tr>
      <td bgcolor="#ffffe6">9th Feb. 2018</td>
      <td>
	<ul>
	<li>Feed forward, back-propagation
	<li>Fully connected layer
	<li>Activation functions: sigmoid, tanh, ReLU, LeakyReLU, ELU, etc.
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/74mfpskzxqpbjlv/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td align="center"> <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/Linear.ipynb">Linear Layer</a>,
	      <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/ReLU.ipynb">ReLU</a>
	</td>
      <td > -- </td>
  </tr>
  <tr>
      <td bgcolor="#ffffe6">15th Feb. 2018</td>
      <td>
	<ul>
	<li>Convolutions: transposed, dilated, fully-connected as convolution, sliding window as convolution
	<li>Max-pooling, Dropout
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/6tm79bgbwtgn2dx/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/Max-Pool.ipynb">MaxPool</a>, 
	      <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/Convolution.ipynb">Convolution</a>, 
	      <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/Transposed%20Convolution.ipynb">Transposed convolution</a>, <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/Dropout.ipynb">Dropout</a>
	</td>
      <td > <a href="https://arxiv.org/pdf/1603.07285.pdf">Convolution arithmetic for deep
learning</a> </td>
  </tr>
    <tr>
      <td bgcolor="#ffffe6">16th Feb. 2018</td>
      <td>
	<ul>
	<li>SoftMax, Cross Entropy
	<li>Data Augmentation, hyperparamter selection
	<li>Weight initialization
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/rccluwz3z0jsaup/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/CEC.ipynb">Cross Entropy</a>, 
	      <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/WeightInit.ipynb">Weight Initialization</a> 
	</td>
      <td > --  </td>
  </tr>  
  <td bgcolor="#ffffe6">22nd Feb. 2018</td>
      <td>
	<ul>
	<li>ConvNet applications
	<li>ConvNet case studies
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/db7gtf95tgu4icp/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td >  
	      --
	</td>
      <td > --  </td>
   </tr>
    <tr>
      <td bgcolor="#ffffe6">23rd Feb. 2018</td>
      <td>
	<ul>
	<li>RNNs, LSTMS
        <li>Visualizing and understanding ConvNets
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/y1v5gw0yy9ca5kv/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > --
	</td>
      <td > --  </td>
  </tr>  
      <tr>
      <td bgcolor="#ffffe6">8th March 2018</td>
      <td>
	<ul>
        <li>Visualizing and understanding ConvNets
	<li>Images that maximize ConvNet class scores, reconstructing images from ConvNet <i>codes</i>
	<li>Deep Dream, Neural Art, Adversarial Examples
	<li>Dimentionality reduction: siamese and triplet networks
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/aigluwg8dqeg9g4/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > --
	</td>
      <td > --  </td>
  </tr>
    </tr>  
      <tr>
      <td bgcolor="#ffffe6">9th March 2018</td>
      <td>
	<ul>
        <li>Other vision tasks: semantic segmentation, object localization, object detection, instance segmentation
	<li>R-CNN, Mask R-CNN, 
	<li>Autoencoders
	<li>Generative modeling: VAEs, GANs
	<li>Case studies: pix2pix, CycleGAN, UNIT
      </ul></td>
      <td>
	<a href="https://www.dropbox.com/s/iv4a8k3ipdqzhrr/L2.pdf?dl=0">Slides</a><br/>
	<a href="https://www.dropbox.com/s/y73abfsswmijahh/L2.pdf?dl=0">Slides</a><br/>
      </td>
      <td > <a href="https://github.com/cs763/Spring2018/blob/master/notebooks/MNIST_GAN.ipynb">MNIST Vanilla GAN</a>
	</td>
      <td > --  </td>
  </tr>
        <tr>
      <td bgcolor="#ffffe6">15th March 2018</td>
      <td>
	<ul>
        <li>Deep Reinforcement Learning (Prof. Shivaram Kalyanakrishnan)	
      </ul></td>
      <td>	
	--
      </td>
      <td > -- </td>
      <td > --  </td>
  </tr>  
      <tr>
      <td bgcolor="#ffffe6">16th March 2018</td>
      <td>
	<strong>Structure from Motion</strong>
	<ul>
        <li>Motion as a cue to inference of 3D structure from images
	<li>Motion factorization algorithm by Tomasi and Kanade for inference of (sparse) 3D structure of a fixed object being observed by a moving orthographic camera (or a rigidly moving object, being observed by a fixed orthographic camera)
	<li>Aspects of the above algorithm: Rank theorem, metric constraints for inference of motion parameters and 3D structure
      </ul></td>
      <td>	
	<a href="https://www.dropbox.com/s/k5crreyat1f0jic/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > -- </td>
      <td > --  </td>
  </tr> 
  <tr>
      <td bgcolor="#ffffe6">22nd March 2018</td>
      <td>
	<strong>Kanade-Lucas Tracking (KLT)</strong>
	<ul>
        <li>Tracking feature-points from a template by estimating motion parameters.
	<li>Finding good features to track.
      </ul></td>
      <td>	
	<a href="https://www.dropbox.com/s/142i7kf3ica5ntl/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > -- </td>
	<td > <a href="http://www.ncorr.com/download/publications/bakerunify.pdf">Lucas-Kanade 20 Years On: A Unifying Framework</a><br/>  </td>
  </tr> 
  <tr>
      <td bgcolor="#ffffe6">23rd March 2018</td>
      <td>
	<strong>Geometric Stereo</strong>
	<ul>
        <li>Orientation parameters for the camera pair and relative orientation.
	<li>Coplanarity constraint for corresponding points
	<li>Derivation and key properties of the Fundamental matrix
      </ul></td>
      <td>	
	<a href="https://www.dropbox.com/s/gnt9b550rusrtu5/L1.pdf?dl=0">Slides</a><br/>
      </td>
      <td > -- </td>
	<td > -- </td>
  </tr> 
  
  
  </tbody>
</table>


