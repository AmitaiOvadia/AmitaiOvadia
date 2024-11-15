<h1>
  Hey There!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
<p align="center">
  <b>Welcome to my GitHub :smile:</b>
</p>
<p align="center">
    <a href="https://www.linkedin.com/in/amitai-ovadia-131865248/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"  width="80" height="22"/>
    </a>
</p>

![alpes compresed](https://github.com/user-attachments/assets/6df80379-80e0-48c6-ab1d-39fc8ba08d4d)


- :books: I’m currently pursuing my master's degree in **Computer Science** at the Hebrew University of Jerusalem, and completed a dual major BSc in **CS & Physics**. 
- My interests include:
  - **Machine Learning**
  - **Deep Learning**
  - **SLAM (Simultaneous Localization and Mapping)**
  - **Image Processing**
  - **3D Computer Vision**
  - **Camera Calibration and Geometry**  
- :microscope: As for my MSc, I'm part of the [Micro-Flight Lab](https://www.beatus-lab.org/) - Our goal Understanding the mechanisms of insect flight and implementing them in biomimetic robots. <br>
- My part is **Developing and utilizing an end-to-end computer vision system**, which includes:
  - **Multi-camera calibration** for capturing high-speed videos (16K fps) of flying insects.
  - Engineering an **ensemble of instance segmentation and pose estimation deep neural networks (DNNs)**; labeling, training, and deploying them to analyze insects’ **flight dynamics**.
  - Performing **3D reconstruction and simulation** of insects’ **wings and body dynamics** using multi-camera detections, applying **novel optimization methods** that have achieved **unprecedented, state-of-the-art results** in the field.
  - **Devising and utilizing several validation methods** to ensure the **stability and accuracy** of the system.
- My other projects include all kinds of machine learning, deep learning and computer vision challenges 

<p align="center">
  <b> The tools I use the most :hammer:</b>
  <br><br>
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" width="80" height="22">
<img src="https://img.shields.io/badge/matlab-%23007ACC.svg?style=for-the-badge&logo=matlab&logoColor=white" width="80" height="22">
<img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" width="80" height="22">
<img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" width="80" height="22">
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" width="80" height="22">
<img src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white" width="80" height="22">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" width="80" height="22">
<img src="https://img.shields.io/badge/skimage-%23F7DF1E.svg?style=for-the-badge&logo=scikit-image&logoColor=black" width="80" height="22">
<img src="https://img.shields.io/badge/opencv-%235C3EE8.svg?style=for-the-badge&logo=opencv&logoColor=white" width="80" height="22">
</p>



<h2 align="center">Explore My Work at <a href="https://www.beatus-lab.org/">Micro-Flight Lab</a></h2>

<p>
  Get a glimpse into the research and development I conducted during my time at the Micro-Flight Lab.
</p>

### 🎥 Experimental Setup

<p align="left">
  Four synchronized and calibrated high-speed cameras, capturing at an impressive 16,000 frames per second (fps), record flying insects in real-time. For context, the wingbeat frequency here is around 200 Hz, allowing us to capture intricate details of wing and body dynamics.
  <br>
</p>
Illustration taken from this <a href="https://journals.biologists.com/jeb/article/226/21/jeb245853/334548/A-hull-reconstruction-reprojection-method-for-pose#supplementary-data" target="_blank">paper</a>.



![cameras setup ilustration](https://github.com/user-attachments/assets/39f03fa6-6329-402b-a157-74e59f697dd7)


### 📹 Raw Video Footage
  Below is a raw video from the lab’s high-speed camera setup:

https://github.com/user-attachments/assets/1ed13019-c875-41ce-ad8b-11bbfa9b6acf

<video width="600" controls>
  <source src="https://github.com/user-attachments/assets/1ed13019-c875-41ce-ad8b-11bbfa9b6acf" type="video/mp4">
  Your browser does not support the video tag.
</video>




### 🎥 Video Analysis Pipeline Output
<p align="left">
  The following videos showcases the output from our video analysis pipeline.
</p>


https://github.com/user-attachments/assets/68df9484-7771-43b7-a4eb-abb94684d480

<video width="600" controls>
  <source src="https://github.com/user-attachments/assets/68df9484-7771-43b7-a4eb-abb94684d480" type="video/mp4">
  Your browser does not support the video tag.
</video>


https://github.com/user-attachments/assets/32de3fc4-4b75-4a7f-87d8-c7543d095f28

<video width="600" controls>
  <source src="https://github.com/user-attachments/assets/32de3fc4-4b75-4a7f-87d8-c7543d095f28" type="video/mp4">
  Your browser does not support the video tag.
</video>

**On the left side**, you’ll see the **hand-picked feature points**, automatically detected across all four views. This detection is powered by a **trained ensemble of deep neural networks**, which **identifies points** in each view independently. These 2D detections from multiple views are later **aggregated using novel optimization technics into optimal 3D points**.

**On the right side**, you’ll observe the **reconstructed 3D points**, enhanced with additional annotations:

* The **green plane** represents the **'stroke plane'**: the imaginary plane through which the insect's wings move during each wingbeat.
* The **three arrows** in the center define the insect's **internal 3D coordinate system**.
* Each wing features **two arrows** representing the **chord and span** (x and y axes) of the wing's coordinate system.

<h2 align="center">🎬 Explore My Visualizations 🎬</h2>
<p align="center">
  Dive into interactive visualizations showcasing my research and analyses.
  
* The **static movie** provides an interactive summary of the flight event, visualizing the positions of the wingtips and the center of mass for each frame. Additionally, it depicts the orientation of the fly at every wingbeat (~70 frames), represented as a cross marker.
* The **dynamic movie** offers an interactive simulation of the flight dynamics across all frames, showcasing the tracked 3D points, the fly's internal moving coordinate system, and the coordinate systems of each wing, represented by the chord and span of the wings

    
Click below to open in a new tab:
</p>
<p align="center">
  <a href="https://amitaiovadia.github.io/AmitaiOvadia/movie_html.html" target="_blank">
    <img src="https://img.shields.io/badge/Static_Movie_HTML-brightgreen?style=for-the-badge" alt="Static Movie HTML"/>
  </a>
  <a href="https://amitaiovadia.github.io/AmitaiOvadia/3d_analysis_with_slider.html" target="_blank">
    <img src="https://img.shields.io/badge/Dynamic_Movie_HTML-blueviolet?style=for-the-badge" alt="Dynamic Movie HTML"/>
  </a>
</p>

