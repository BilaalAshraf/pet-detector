# pet-detector

 This program was created to help pet owners locate their cats/dogs if they got lost. A backyard security camera will record the last time the pet was seen and will be able to seperate the owners cat/dog from other cats/dogs by identifying species.

## The Algorithm

The project includes my-recognition.py which is a small python program used to classify images. It takes an image path as an input and uses jetsons image net classifier to classify the image as a specific cat or dog species. The jetson image net is a pretrained model that can classify hundreds of images.

## Running this project

To run the project
`python3 my-recognition.py image_file`

example:

` python3 my-recognition.py train/persian/Persian_1.jpg`


2. Make sure to include any required libraries that need to be installed for your project to run.

[View a video explanation here](https://youtu.be/Rf-SNP1QJ8w)
