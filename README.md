<br/>

# About the Project  

This software recognises the numerical digit (0-9) from the image containing any digit (currently limited to 1 digit per file). This is accomplished with the help of preprocessing of each image done using OpenCV library in accordance with the MNIST database recommendations.

The artificial neural network is trained from the MNIST training data set available at its official website.

End user can browse any file (image) containing the handwritten digit, or he can capture a new image from the attached camera device.

---
## Prerequisites before using this software :

1. Make sure you have **Python 3.x** setup on your operating system.  
   
2. Install the follow libraries to meet the dependencies :  
    (i) **Tensorflow**  
    (ii) **OpenCV**  
	(iii) **kivy** *(and its supporting gstreamer libraries)*  
    (iv) The supporting libraries like numpy,pil and all others *(which are automatically installed while installing the above mentioned libraries)*  

3. You need a working camera for the image capture option to work.

---

## Compiling and Running :

Execute `main.py` using the terminal of your choice.

_Example Syntax_ : `python3 main.py`

---

### Important Usage Instructions : 

To capture a new image, press C to pause the captured video stream, then press C to capture the image or any other key to abort the capture operation.

---

## Screenshots

<p float="left">
   <img src="https://github.com/akashpanda122/digit-recognizer/blob/main/cap1.png" alt="hand reader screenshot 1" width=300px />
    &emsp;
   <img src="https://github.com/akashpanda122/digit-recognizer/blob/main/cap2.png" alt="hand reader screenshot 2" width=300px />

</p>

<p float="left">
   <img src="https://github.com/akashpanda122/digit-recognizer/blob/main/cap3.png" alt="hand reader screenshot 3" width=300px />
    &emsp;

</p>
