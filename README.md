# Create-Face-Data-from-Images
Using OpenCV Face Detection Neural Network to separate faces from list of images.

### Description
This project uses OpenCV's Face Detecttion Neural Network to detect faces in images and perform the following:

* Extract faces from a set of images using **face_extractor.py** and store them in the folder **faces**
This would make extracting faces very easy and could be used for further analysis.

## Setup

### Python Virtual Environment
1. Open the terminal
2. Clone the repository to your local machine
3. Navigate inside the folder
4. Create a virtual environment(recommended)
5. Activate virtual environment

### pip3
1. Open the terminal
2. Clone the repository to your local machine
3. Navigate inside the folder
4. Install all dependencies using `pipenv install -r requirements.txt`

## Usage

### Extract faces
1. Create a folder with the name **images**
2. Put all the images inside the folder **images**
3. In the terminal, use the command `python face_extractor.py` to grab and export faces
4. The faces will be in the folder **faces**
