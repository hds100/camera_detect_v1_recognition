<div align="center">

# Camera_detect_v1 👁 [◉°]

</div>

Security camera recognition project through photos or videos, using roboflow and yolov8.

The project has a dataset of more than 580 images using testing, validation and training methodology. It was my first project of its kind, so it is not fully operational in terms of precision in its first version.

For real average camera detection accuracy per photo, I estimate between 55 to 70% (although in roboflow the average accuracy is 82%) and for videos it drops to 10 to 25% (it will depend on how many megapixels the recording camera has). **There are many variables that can affect these percentages, but remember: this is a project that is in its first version.**

**The photo below is an example of model detection, not a photo of the dataset. You can test the model, view metrics, and check the dataset at the link in Step 1.**

<div align="center">

![camv1](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/e99da3b7-ce3b-44ca-80e9-9219507208d3)
![coordinates](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/c40cc89a-3c58-4e55-8acb-0236e7032072)



</div>

<div align="center">

# Training Metrics

![metrics](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/2a64f34c-bf66-4dc2-b281-d9a52e7e2e4b)


</div>


## Step 1


First, you need to access the dataset in roboflow [clicking here.](https://universe.roboflow.com/model-rg/camera-detection-wwncv) The image below is the model's home page. 

<div align="center">

![roboflow home](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/710a51ea-c707-428a-b330-a978a94aa69c)

</div>

## Step 2

Now that you are on the home page, open another tab in your browser. Then search for security camera footage or even a photo of one you took. With this photo saved in a folder on your computer, to avoid any bugs or errors, do not drag the image but click on **browse your device.**

<div align="center">

![step 2](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/8831f9cb-d150-4dbd-9dde-64601a4a16ca)

</div>

## Step 3

**It is very important that you choose an image outside the dataset, as those in the dataset have already been trained and will therefore give a false positive.** With the image chosen, the screen below should appear:
<div align="center">
  
![step 3](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/c1128d1e-bd97-419f-a6c3-d3cbd34e5d25)

</div>

**That's it, you've tested the model! If you want to better view the recognized camera, you can adjust the confidence threshold and overlap threshold. Remembering that this model is only for security cameras. Webcams, camcorders, cameras and other similar devices do not apply.**

<div align="center">
  
# Miscellaneous

</div>

If you want to view images, dataset, model, documentation to implement in API's and other data in the health check dataset, simply access one of the options in the panel on the side.

<div align="center">
  
![others](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/dea80edc-5aac-4832-953c-b5d58ec77dc1)

</div>

And to prove that it is my own:

<div align="center">
  
![original](https://github.com/hds100/camera_detect_v1_recognition/assets/148555673/640a17b9-93df-46a0-9742-24711f0f9eba)

</div>

**If you made it this far, thank you very much! It was very interesting to do this project, as it was my first experience with machine learning. As it was a project done as a hobby to learn more about object recognition, there are many variables that I did not consider, perhaps I did not choose the best training model, the best annotation for the images (box, polygon, etc.), the best guidelines, image resolutions and the ideal dataset is to have at least 1000 images. Therefore, the accuracy is not the best, I consider a reliable accuracy above 95%.**
