---
layout: default
---

<h1 align="center">VisionMD: An Open-Source Tool for Video-Based Analysis of Motor Function in Movement Disorders</h1>
<div align="center">
  <a href="https://www.linkedin.com/in/gabrielaacevedot/" target="_blank">Gabriela T. Acevedo T.</a><sup>1</sup>, Florian Lange<sup>2</sup>, Carolina Calonge<sup>1</sup>, Robert Peach<sup>2</sup>, Joshua K. Wong<sup>3,5</sup>, <a href="https://www.linkedin.com/in/diego-guarin/" target="_blank">Diego L. Guarin</a><sup>1,2</sup>
</div>
<br>
<sup>1</sup>Movement Estimation and Analysis Laboratory, Department of Applied Physiology and Kinesiology, University of Florida.
<br>
<sup>2</sup>Department of Neurology, University of Würzburg.
<br>
<sup>3</sup>Fixel Institute for Neurological Disease, University of Florida.
<br>
<sup>4</sup>Crayton Pruitt Family Department of Biomedical Engineering, University of Florida.
<br>
<sup>5</sup>Department of Neurology, University of Florida. 

# Abstract
<div style="background-color: #C7EFCF; padding: 10px; border-radius: 5px; margin: 20px 0;">
  <p>Assessing motor function is crucial for Parkinson’s disease (PD) management, yet  the widely used MDS-UPDRS has significant limitations, largely owing to rater subjectivity. We introduce VisionMD, an open-source software for semi-automatic motor function analysis from videos of the MDS-UPDRS motor tasks, enhancing objectivity and accessibility. Two datasets were analyzed to validate VisionMD, each featuring 12 PD patients performing a Finger Tapping (FT) task under varying interventional conditions: Deep Brain Stimulation (DBS-ON/OFF) and dopaminergic medication. Significant differences were observed in movement variability between DBS-ON/OFF and movement speed between MED-ON/OFF. VisionMD demonstrated excellent inter-rater reliability (ICC = 0.96 – 1.00) compared to traditional MDS-UPDRS evaluation (ICC = 0.74). VisionMD provides a scalable, objective tool for assessing motor symptoms in persons with movement disorders, offering high reliability and potential for widespread clinical and research use</p>
</div>

# Pipeline
<div align="center">
    <img src="files/VisionMD.png" alt="Pipeline" />
</div>

# Tutorials
[![Watch the video](https://img.youtube.com/vi/nEziXfARw8o/maxresdefault.jpg)](https://youtu.be/nEziXfARw8o)
[![Watch the video](https://img.youtube.com/vi/jZDgEBjXwP8/maxresdefault.jpg)](https://youtu.be/jZDgEBjXwP8)

# Installation Instructions - MacOs

1. **Unzip the File**  
   Once downloaded, unzip the file.

2. **Launch the Application**  
   Double click on `VisionMD`.

3. **Open the Terminal**  
   A Terminal window will open, showing some progress while the program starts.

4. **View the Startup Message**  
   After a few seconds, you will see the following message in the Terminal:

   ```bash
   Django version 4.2.11, using settings 'backend.settings'
   Starting development server at http://127.0.0.1:8000/
   Quit the server with CONTROL-C.
    ```
5. **Open Google Chrome**  
   This program has only been tested with Google Chrome; other browsers might provide unexpected behavior.

6. **Access the Application**  
   In the URL bar, type: `http://127.0.0.1:8080` and hit Enter.  
   VisionMD will open, and you are now able to use the software.

7. **Close the Application**  
   Once you are done using VisionMD, return to the Terminal window and hit `CONTROL + C`.  
   Close the Terminal window and then close Google Chrome.

# Sample Videos
Click to get sample videos to process using VisionMD
<br>
<br>
<div align="center">
  <a href="https://github.com/mea-lab/VisionMD-Tutorial/tree/main/sampledata/Videos" target="_blank">
    <img src="files/sample_data.png" alt="Sample Data" width="500">
  </a>
</div>

### How to download videos from GitHub
1. Select the video you want to download
2. Click the download button
3. <div align="center">
    <img src="files/download_video.jpg" alt="Download Video" />
</div>

# Kinematic Measures Sample Data

This data was collected from two cohorts of Parkinson's Disease patients to illustrate VisionMD's capability in assessing the impact of different therapies. Each patient underwent two recording sessions: one with their therapy "on" and another with it "off." The therapies assessed included:

1. **Deep Brain Stimulation (DBS)**
2. **Dopaminergic Medication**

The Excel file contains each row as a separate recording. For more details and to download the data, visit the [Kinematic Data GitHub Page](https://github.com/mea-lab/VisionMD-Tutorial/tree/main/sampledata/KinematicData).
<br><br>
A <a href="https://github.com/mea-lab/VisionMD-Tutorial/tree/main/sampledata/KinematicData/data_analysis.ipynb">sample code</a> analyzing the data to reproduce results presented in the paper is provided. Analysis includes a paired t-test for each kinematic measure to compare "on" and "off" therapy sessions. This analysis is performed separately for patients undergoing Deep Brain Stimulation and those receiving Dopaminergic Medication, allowing users to assess the effects of each therapy on motor function.
