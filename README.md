# Maleria-Detection-on-Image-Dataset-Using-Machine-Learning-and-OpenCV

# Problem Statement :
## Detecting whether the human cell given in image is infected by maleria or not.

Here I used some common techmoques of Computer Vision and Machine Learning.
Here the project deals with image data.

## Image dataset link : https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

Samples drawn from NIH Malaria dataset which are malaria infected parasite red blood cells. The images show various forms of parasite in the red blood cells.

![Samples-drawn-from-NIH-Malaria-dataset-which-are-malaria-infected-parasite-red-blood](https://user-images.githubusercontent.com/19407823/94339059-ad31cc80-0014-11eb-9a1b-b8adb3c35cbd.jpg)

### Steps performed : 

1. Read the image.
2. GreyScale the image.
3. Perform the contour detection
4. Get the 4 areas of lagest encountered countours.
  ( for uninfected cell image, there will be only 1 countour i.e. cell boundary )
  
5. Store the data obtained into the SCV file.
   The dataset looks like this : 
   
   ![maleria-data](https://user-images.githubusercontent.com/19407823/94339271-4c0af880-0016-11eb-925c-80252418b7d6.PNG)
   <br>
6. Build a classifier using Scikit-learn

