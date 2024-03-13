# Atrium_Segmentation
This project trains a UNet for a medical image segmentation task: segmenting the atrium from cardiac MRI images.

![image](https://github.com/cyuanfan/Atrium_Segmentation/blob/master/demo_video/artium%20segmentation.gif)

# Cardiac MRI Data 
The data is provided by the medical segmentation decathlon. (http://medicaldecathlon.com/)

[MRI Data](https://drive.google.com/file/d/1wEB2I6S6tQBVEPxir8cA5kFB8gTQadYY/view?usp=sharing)

# UNet Weights

<img src="https://github.com/cyuanfan/Atrium_Segmentation/blob/master/U-Net.png" width=75% height=75%>

[Weights](https://drive.google.com/drive/folders/1z0VvByCyNHrRfcZZfCdtngNykVOuo1Ux?usp=drive_link)

# Result and Demo

Dice Score = 0.9288

[Demo-1](https://www.youtube.com/watch?v=IDDKDRZ0Ajg)
[Demo-2](https://www.youtube.com/watch?v=xXLJWxG7MIc)
[Demo-3](https://www.youtube.com/watch?v=QGxEBs3Sd7E)

# Packages Install
In order to avoid package version conflicts, I suggest using Anaconda to create a virtual environment for this project.

You can enter the following command in the Anaconda Prompt to create an environment and install all the required packages.

```bash
conda env create -f environment.yml
```
