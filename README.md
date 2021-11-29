# Plant Disease Detection

It is a plant disease detection project...
cnn.py is used to train and test the model
ui.py is used for finding the disease in the given leaf by the user

PACKAGE REQUIREMENTS
  numpy (pip install numpy)
  tqdm (pip install tqdm)
  TensorFlow
  openCv
  matplotlib
  
The model successfully recognizes three types of plant leaf diseases:
Bacterial spot
Yellow leaf curl virus
Late Blight 
It is also able to give out some remedies regarding the detected disease.

We used tkinter to deploy our model. Following are some images of the process to use the model.

![step1](./images/step1.PNG?raw=true "Title")
 
Now the user has to select an image for testing,

![step2](./images/step2.PNG?raw=true "Title")

Thus, the user selected image can be seen and when pressed on “Analyse Image”, we get the leaf defects.

![step3](./images/step3.PNG?raw=true "Title")

We get the status of the health of the leaf and the disease name from which it's infected, we can further check for remedies.

![step4](./images/step4.PNG?raw=true "Title")

Remedies which we get, can be used for treating the plant.

