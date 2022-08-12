# simple-live-face-recognition

This is a simple live facial recognition project I wrote in Python

The setup is a little tough. It relies on the face_recognition library, and to use that you must first install a C++ compiler, and then cmake and dlib. After that you can install the face_recognition library and opencv. Numpy is also required but I think that comes with one of the other libraries so that shouldn't be a problem.

If you run the program it should open up a window with live video streamed your webcam. From there you can start by testing things out, and for that I've included a few images of some familiar faces in the "img" folder. If you Google an image of Elon Musk, for example, and hold your phone up to your computer screen it should be able to detect and label him properly.

If you want the program to detect your own face, just put a picture of yourself in the "img" folder, and it should detect and label you accurately in real time.
