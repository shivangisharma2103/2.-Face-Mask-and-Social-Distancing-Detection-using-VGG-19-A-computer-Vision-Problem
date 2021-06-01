# 2.-Face-Mask-and-Social-Distancing-Detection-using-VGG-19-A-computer-Vision-Problem

(https://www.kaggle.com/shivangi21/face-mask-detection)
The main objective was to build a Deep Learning Model to detect if a person is wearing mask or not and further check if social distancing norms were being followed or not. I used Haar feature-based cascade classifier for face detection. The Haar Cascade Model was trained to detect faces in order to obtain bounding box coordinates of faces in images. I calculated the Social Distancing validity according to the norms pertaining in India and marked Red boxes for those violating and green for those abiding them. Further I used VGG 19 to detect face masks. The model achieved 99% accuracy on the trained data. The model was able to identify a mask in the test data too. Then we integrated with Haar Cascade and tested it on the test data. We correctly got social distancing as well as masks predicted at the end.

