# GMIG

CNN model trained to be able to classify gestures in order to build a more inclusive gaming experience for everyone.

# Installation and Running

The model can be tested, independently or with the PyAutoGUI output through the ```test-model.ipynb``` file. 

Libraries needed: numpy, cv2, tensorflow, pyautogui, opendatasets, pandas, sklearn, os.


# Code Structure
- ```ML_GestPlay.ipynb```
  - Primary notebook for the model training. Model was trained on Google Colab to take advantage of their T4 GPU runntime.
- ```test-model.ipynb```
 - Primary testing notebook. Contains all the code for evaluating the model, as well as evaluating how feasible it is to integrate model output to keyboard inputs. 
- ```gesture_mode.h5``` 
  - The model itself.
- ```./04/```
  - Directory with images used during the testing process. These are from the dataset that we split for test and train. 