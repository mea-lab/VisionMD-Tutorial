---
layout: default
---
<h1 align="center">VisionMD: An Open-Source Tool for Video-Based Analysis of Motor Function in Movement Disorders</h1>
<div align="center">
  Gabriela T. Acevedo T.<sup>1</sup>, Florian Lange<sup>2</sup>, Carolina Calonge<sup>1</sup>, Robert Peach<sup>2</sup>, Joshua K. Wong<sup>3,5</sup>, Diego L. Guarin<sup>1,2</sup>
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

<p align="center">
  <a href="https://github.com/mea-lab/VideoAnalysisToolBackend/tree/dev">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="80">
  </a>
  &nbsp;&nbsp; 
  <a href="https://www.dropbox.com/scl/fi/u43mwolb57ph6834v07d2/VisionMD_MacOS.zip?rlkey=bgmthf22fxy8g6chsqo3r8d2k&e=1&st=6jl50jcg&dl=0" target="_blank">
    <img src="download_logo.jpg" alt="Download" width="80">
  </a>
</p>

## Abstract
<div style="background-color: #D3D3D3; padding: 10px; border-radius: 5px; margin: 20px 0;">
  <p>VisionMD is an innovative, open-source software tool designed to enhance the assessment of motor function in patients with Parkinson’s disease (PD) through automatic video-based analysis of standardized motor tasks from the MDS-UPDRS Part III. Traditional clinical assessments, while widely used, rely heavily on the expertise of trained raters, which can lead to inconsistencies and limitations in diagnosing and managing early-stage PD. VisionMD addresses these challenges by offering a user-friendly interface that allows clinicians to process videos of motor tasks with minimal technical expertise. The software employs advanced algorithms to automatically detect subjects, track body movements, and quantify kinematic features such as speed and amplitude. In our studies, VisionMD demonstrated excellent inter-rater reliability, achieving Intraclass Correlation Coefficients (ICCs) ranging from 0.96 to 1.00 for kinematic features, significantly outperforming traditional MDS-UPDRS scores, which exhibited ICCs around 0.74. By providing objective, consistent, and transparent evaluations of motor function, VisionMD facilitates enhanced clinical decision-making and research capabilities. Furthermore, its local processing capabilities ensure data privacy and security, making it accessible for widespread use in both clinical and research settings. Overall, VisionMD stands as a promising advancement in the objective assessment of motor performance, aiming to improve the standardization and accuracy of evaluations in the management of Parkinson’s disease and other movement disorders.</p>
</div>

## Pipeline
<div align="center">
    <img src="VisionMD_Pipeline.png" alt="Pipeline" />
</div>

## Tutorial - Full
[![Watch the video](https://img.youtube.com/vi/nEziXfARw8o/maxresdefault.jpg)](https://youtu.be/nEziXfARw8o)

## Tutorial - Single Task
[![Watch the video](https://img.youtube.com/vi/jZDgEBjXwP8/maxresdefault.jpg)](https://youtu.be/jZDgEBjXwP8)

## Download the Tool - MacOs

[![Download VisionMD](https://img.icons8.com/material-outlined/50/000000/download--v1.png)](https://www.dropbox.com/scl/fi/u43mwolb57ph6834v07d2/VisionMD_MacOS.zip?rlkey=bgmthf22fxy8g6chsqo3r8d2k&st=6jl50jcg&dl=0) 

## Installation Instructions - MacOs

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
   (This program has only been tested with Google Chrome; other browsers might provide unexpected behavior.)

6. **Access the Application**  
   In the URL bar, type: `http://127.0.0.1:8080` and hit Enter.  
   VisionMD will open, and you are now able to use the software.

7. **Close the Application**  
   Once you are done using VisionMD, return to the Terminal window and hit `CONTROL + C`.  
   Close the Terminal window and then close Google Chrome.

## Sample Data
**Download sample videos to process using VisionMD**
https://github.com/mea-lab/VisionMD-Tutorial/tree/main/sampledata
