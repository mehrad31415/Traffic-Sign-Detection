# Traffic-Sign-Detection
This was the final project for the computer vision course.


In this paper our goal is to develop a computer vision algorithm for the recog- nition of a particular class of road signs in images. More precisely, our re- search is devoted to creating a pipeline to detect prohibition signs within an image. The prohibition signs we have included in our dataset are signs A1, C1, C6 to C22a, F1, F3, F5, F7, and F10 in the overview of Dutch road signs at https://en.wikipedia.org/wiki/Road signs in the Netherlands [1]. The main feature all these signs have in common is that they are in the shape of a cir- cle and consist of a red annulus; except for the C2 (No Entry) sign which is slightly di↵erent. Therefore, in simple words, we aim to develop an algorithm to spot the red annuli that appear in an image. By doing so, we conclude that the image contains a prohibition sign. Accordingly, our research project consisted of the following steps: (1) Practical field work (collecting data) (2) Increasing the size of our dataset by using image processing technics (3) Prepro- cessing and preparing our data for recognition of prohibition signs (4) Applying masking technics for prohibition sign detection (5) Applying Hough circle trans- formation for prohibition signs detection. These sections were the core of our research. However, given the relatively high error ratio of our technique we went further and examined more sophisticated computer vision techniques. (7) Ap- plying template matching for prohibition signs detection (8) Applying Feature Matching for prohibition signs detection (9) Applying Blob Detection for pro- hibition signs detection (10) Finally, using Machine Learning we built a model to detect whether an image contains a prohibition sign or not. After developing our ML algorithm, we will run it on the dataset to calculate the precision and recall of our algorithm. In all sections we will compare the technics and discuss how they e↵ect the quality of the detection. As a result, we will aim to reach an optimized algorithm with a high detection accuracy rate. In all steps of our research, we only aimed to detect tra c signs, i.e., whether in an image a tra c sign is found or not. However, we will at the end discuss further work that can be applied on our algorithm for tra c sign recognition, i.e., what kind of tra c sign is in our image.
