# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
> I wrote a pre-trained image classifier to identify dog breeds using python

## Table of Contents
- [Pre-trained-Image-Classifier-to-Identify-Dog-Breeds](#pre-trained-image-classifier-to-identify-dog-breeds)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Technologies Used](#technologies-used)
  - [Features](#features)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Project Status](#project-status)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)
  - [License](#license)


## General Information
- My city is hosting a citywide dog show and i have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. 
The registration system tags the images based upon the biographical information. Some people are planning on registering pets that aren’t actual dogs.I used an already developed Python classifier to make sure the participants are dogs.
- Principal Objectives
<ol><li> Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.</li>
<li>Correctly classify the breed of dog, for the images that are of dogs.</li>
<li>Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.</li>
<li>Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.</li></ol>


## Technologies Used
- ImageNet - a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images.
- Python - version 3.0


## Features
- ResNet Model Architecture
- AlexNet Model Architecture
- VGG Model Architecture 


## Setup
- To run this project, it is required you've already installed Python 3 on your operating system. Check out this guide on installing python [Installing Python Guide](https://github.com/PackeTsar/Install-Python)
- Download the workspace files and keep all in one folder. There are two folders of interest in which we're classifying, the pet_images folder and the uploaded_images folder.
- Use terminal/command prompt to run projects
- Attached is the hints file for each python program for guidance 


## Usage
- Open a terminal from the workspace folder, and run 
		`check_images.py`
    >The program should successfully classify the 40 images from the pet_images folder
- Open a terminal from the uploaded_images folder, and run
		`sh run_models_batch_uploaded.sh
    >This will run check_images.py using all three model achitectures to classify the four images in the uploaded_images folder outputting their results files into the workspace using .txt format 
classify the 40 images from the pet_images folder. In this section, you will upload 4 images to the uploaded_images folder
- Directions for Finding Images and Uploading Images
    >Below are directions for finding images and processing them so they can be classified by the check_images.py program.
  <ol><li>Process the images so that:
		Images are in jpeg format with extension jpg
		Images are approximately square in shape (their height and width are approximately the same numbers of pixels).</li>
  <li>Find the following 3 images (or take the following 3 pictures):
		Dog Image - named Dog_01.jpg. Make sure you know the breed of dog that the image is of.
		Pet or Animal Image that's not a dog - named Animal_Name_01.jpg , where Animal_Name is the name of the animal in the picture. This name is formatted such that if more than one word makes up the animal name those words are separated by an underbar ( _ ).
			For example:
				Image of a Black Bear is named Black_bear_01.jpg
				Image of a Frog is named Frog_01.jpg</li>
	  <li>An image of something that's not an animal - named Object_Name_01.jpg, where Object_Name is the name of the object in the picture. This name is formatted such that if more than one word makes up the object name those words are separated by an underbar ( _ ).
		For example:
			Image of a Coffee Mug is named Coffee_mug_01.jpg
			Image of a Bucket is named Bucket_01.jpg</li>
  <li>Create a fourth Image of a Dog using Dog_01.jpg
		Using Dog_01.jpg image horizontally flip the image and name it Dog_02.jpg. This will mean that Dog_02.jpg is a mirror image of Dog_01.jpg. If you are having difficulty with the horizontal flip alteration of Dog_01.jpg, just rotate Dog_01.jpg image by 180 degrees so that Dog_02.jpg is an upside-down version of Dog_01.jpg.</li>
	<li>Upload all four images to the uploaded_images folder within the Project Workspace - Uploaded
		Double click on the uploaded_images folder within the Project Workspace - Uploaded.
		Next, click on the white + symbol above />home>workspace>uploaded_images text
		Next, select Upload File from the dropdown menu
		Next, select one of the four files to upload to the uploaded_images folder and click on the Open button
		Repeat the same process to upload the rest of the four files to the uploaded_images folder</li>
    

## Project Status
Project is: completed


## Acknowledgements
Give credit here.
- This project was based on improving my programming skills using Python by [Udacity](https://learn.udacity.com).
- Many thanks to Udacity and my sesssion lead abdulla at Udacity for the support.


## Contact
Created by [Emmanuel Samuel](https://www.linkedin.com/in/emmanuel-samuel-168255143) - feel free to contact me!


## License
This project is open source and available under the [Udacity License]

