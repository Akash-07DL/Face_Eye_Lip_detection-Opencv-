:GoogleColab:

:Opencv:

# Face_Eye_Lip_detection_using_Opencv-

Face detection is a computer vision technology that helps to locate/visualize human faces in digital images. This technique is a specific use case of object detection technology that deals with detecting instances of semantic objects of a certain class (such as humans, buildings or cars) in digital images and videos. With the advent of technology, face detection has gained a lot of importance especially in fields like photography, security, and marketing.

# Objective-

Objective is to detect Face, Eye and Lip. **(On Google Colab)**

# Face Detection-

Face detection is a technique that identifies or locates human faces in digital images. A typical example of face detection occurs when we take photographs through our smartphones, and it instantly detects faces in the picture. Face detection is different from Face recognition. Face detection detects merely the presence of faces in an image while facial recognition involves identifying whose face it is.

Face detection is performed by using classifiers. A classifier is essentially an algorithm that decides whether a given image is positive(face) or negative(not a face). A classifier needs to be trained on thousands of images with and without faces. Fortunately, OpenCV already has two pre-trained face detection classifiers, which can readily be used in a program. The two classifiers are: Haar Classifier and Local Binary Pattern(LBP) classifier.

Used only Haar Classifier to detect face, eye, and lip.

# Steps: 

1. Upload an image of Human.
2. `< face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + "haarcascade_frontalface_default.xml")
eye_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + "haarcascade_eye.xml")
lip_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + "haarcascade_smile.xml")>`

3.Drawing the Bounding box around the Face, Eye and Lip.
