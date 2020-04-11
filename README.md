# Handwriting-to-Digital-Text
This repository aims at building a system for conversion of handwritten text to digital text. This project uses the core RNN achitecture described in the paper https://arxiv.org/pdf/1601.06581.pdf . The code is made into ready to run Google Colab notebook.

# How to run
1. Click on the this link https://drive.google.com/open?id=1w06mzRKfi1AjcuutJTcv1vM5lIWlKVeg to access the link.
2. Click on 'Open with Google Colaboratory'.
3. Now run each cell in order as arranged in the notebook.
4. To test this on your own image, please upload your image. Then go to the main.py file with path '/content/content/content/content/SimpleHTR/src/main.py' and change the path in the line I = cv2.imread('/content/handwriting2.jpg') and run the cells agin.

# Results
I have worked this for single line input. The input image is


![Image input line](https://github.com/nikhilrathaur/Handwriting-to-Digital-Text/blob/master/handwriting2.jpg)


The output is saved in the result.txt file. I have put the screeshot of the output txt file below and here https://github.com/nikhilrathaur/Handwriting-to-Digital-Text/blob/master/result.txt

![Image Output Screenshot](https://github.com/nikhilrathaur/Handwriting-to-Digital-Text/blob/master/Screenshot%20(587).png)

Boxes are made around each word and then they are converted into a sentence in order. The word detection is given below
![Image of word detection](https://github.com/nikhilrathaur/Handwriting-to-Digital-Text/blob/master/new.png)

In case of any query, please get back to me on nikhilrathaur1998@yahoo.com
