# Gender-and-Age-Detection   <img alt="GitHub" src="https://img.shields.io/github/license/abdelkhalek-haddany/Age-Gender-predection-using-CNN">

<h2><a href="https://www.canva.com/design/DAF5M2rSX8w/EMkFTmvGx_P2qjQyUFUtmQ/edit?utm_content=DAF5M2rSX8w&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">Sample presentation about this project</a></h2>
<h2>Objective :</h2>
<p>To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.</p>

<h2>About the Project :</h2>
<p>In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. I used the models trained by <a href="https://susanqq.github.io/UTKFace/">UTKFace</a>. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.</p>


<h2>Additional Python Libraries Required :</h2>
<ul>
  <li>OpenCV</li>
  
       pip install opencv-python
</ul>
<ul>
 <li>sklearn</li>
  
       pip install sklearn
</ul>
<ul>

<li>Tensorflow</li>
  
       pip install tensorflow
</ul>
<ul>

<li>matplotlib</li>
  
       pip install matplotlib
</ul>

<h2>The contents of this Project :</h2>
<ul>
  <li>2.1_train_age_model.ipynb</li>
  <li>2.2_train_gender_model.ipynb</li>
  <li>3.1_Pred_Final.ipynb</li>
  <li>TestModels.ipynb</li>
 </ul>
 
 <h2>Usage :</h2>
 <ul>
  <li>Download my Repository</li>
  <li>Open your Command Prompt or Terminal and change directory to the folder where all the files are present.</li>
  <li><b>Detecting Gender and Age of face in Image</b> Using the TestModels.py file</li>
  </ul>
  
