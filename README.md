# Handwritten Emoji Captcha Detector
This captcha solver has been developed using deep learning and convolutional neural networks with the use of OpenCV for character segmentation. 
It can be used to recognize handwritten captchas consisting of different letters as well as emoji. 
The model was trained on Google Colab using the hand drawn dataset in the form of a csv file. The model was trained to achieve a training accuracy of 
~97% and a test accuracy of ~98%.

![image](https://user-images.githubusercontent.com/78314796/173179955-f411de3e-8e10-4683-bda1-a83ab3e36e4b.png)

# Special Features of The Model
1. This model can recognize captchas consisting of letters and numbers rotated at a max. angle of 30 deg.
2. Can detect captchas having letters and emoji of variable thickness and size.
# Characters
The characters on which the model was trained are given in the file characters.txt. To decode captchas you need to input the image paths in the main.py file and run the file. The python libraries required for this are mentioned in the requirements.txt file. The csv file on which the model was trained is also available. A few sample captchas have also been provided in the sample captchas folder.
Emoji in the character set are Checkmark, Cloud, Croissant, Heart, Laugh, Smile, Sun.
