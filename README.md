# Face-Detection
Face Detection a university project for the Computer Vision course.

This project compares two images and calculate the euclidean distance between them.

I tested it on two images of Linus Torvalds and two images of myself.

## Requirements

This python project needs this packages:

- cv2 (opencv)
- imutils
- matplotlib
- scipy
- scikit-image
- dlib
- tkinter

These packages can be installed with the follows commands.

For Python2:
```
$ pip install -r requirements.txt
$ sudo apt install python-tk
```

For Python3:
```
$ pip3 install -r requirements.txt
$ sudo apt install python-tk

```

Remember that install dlib on python3 will take a lot of time, CPU and RAM.

Moreover, this project needs the dlib face recognition models and the shape face predictors, so here the download link:

[dlib_face_recognition_resnet_model_v1.dat.bz2](https://github.com/davisking/dlib-models/raw/master/dlib_face_recognition_resnet_model_v1.dat.bz2)
[shape_predictor_68_face_landmarks.dat](https://github.com/AKSHAYUBHAT/TensorFace/raw/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat)

(put them in the main directory of the project).


## Usage
If anyone wants to run this project with others pictures can put in **img/sample1** the first picture like **"picture.jpg"** and the second picture in **img/sample2/** with the same name of the first picture plus "2" like **"picture2.jpg"**, the project will load automatically these images, get the faces in the picture and print them in the directory **img/faces/** (if not, it means that these images are not valid for the project).

Well, now you can just run the project with jupyter-notebook and see the distance between the images.

### Example

[Here]("docs/Face Detection.pdf") you can get the output of the project.
