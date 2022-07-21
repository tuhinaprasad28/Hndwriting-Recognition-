"# Handwriting-Recognition-" 
Problem Statement

Handwriting is the most common way of transmitting and organizing information. Mechanical and digital technology have gradually begun to replace conventional handwriting methods for the sake of efficiency and time. Despite the obvious advantages of these modern technologies, the importance of handwritten communication cannot be underestimated. It is not fair for the world to retreat to pen and paper in the face of the current data deluge and perpetual sense of urgency that exists in practically every major industry. 

Handwriting recognition (HWR) technology on tablets and other devices, on the other hand, allows you to keep the cognitive benefits of handwriting without going back to the days of overflowing filing cabinets. 

In this project we strive to solve this problem by extracting text from handwritten image files using deep convoluted neural networks and computer vision.


Project Dataset

The model was trained using the Kaggle Alphabet Dataset: A_Z Handwritten Data.csv Dataset. There are 3,72,450 photos in the collection, with 26 labels for all the English alphabets. It was also utilized to create a program that recognizes handwritten text on paper. The Dataset contains 785 columns and is of 699 MB. Each letter in the image is center fitted to a 20 X 20-pixel box, and the dataset comprises of 26 labels (A-Z) containing handwritten graphics of size 28 X 28 pixels. Each image is stored as Gray level. The images are taken from NIST(https://www.nist.gov/srd/nist-special-database-19) and NMIST large dataset and few other sources which were then formatted as mentioned above.


Project Scope

Keeping the timeline in mind the current scope of the project is to recognize the alphabets in English language having 26 characters. The input images will be grayscale with limited size, resolution and orientation. Lower case alphabets are written in a number of different ways by different writers, whereas capital letters are written in a similar manner by all writers that’s why for this project, we will consider only uppercase letters. 

Individual handwriting detection is easier to detect than cursive which is connected and poses more issues with evaluation. It is difficult to interpret handwriting with no distinct separation between characters. Since we are trying to design a semi-trained model of a Neural Network, the computation time and power will also be very high. 

