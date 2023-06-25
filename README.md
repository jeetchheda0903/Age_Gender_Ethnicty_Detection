Title : 
AGE_GENDER_ETHNICITY_DETECTION

Objective :
Developed a web application using machine learning and convolutional neural networks (CNNs) to accurately classify age, gender, and ethnicity.

About the Project :
In this Python Project, I had used Machine Learning to accurately identify the age, gender and ethnicity of a person from a single image of a face.  
The predicted gender may be one of (Male) and (Female), the predicted age may be one of the following ranges-
(0 – 8), (9 – 16), (17 – 24), (25 – 32), (33 – 40), (41 – 48), (49 – 56), (57 – 64) and the predicted ethnicity may be (White), (Black), (Asian), (Indian), (Others).
It is very difficult to accurately guess an exact age & ethnicity from a single image because of factors like makeup, lighting, obstructions, and facial expressions. 
And so, I made this a classification problem instead of making it one of regression.

Dataset :
For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it here. 
This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging. 
The images have been collected from Google.
The models I used had been trained on this dataset.

Additional Python Libraries Required :
OpenCV
   pip install opencv-python
numpy
   pip install numpy
tensorflow
   pip install tensorflow

The contents of this Project :
AGE
saved_model.pb (The protbuf file contains the graph definition as well as the weights of the model/We can use this to run the trained model.)
labels.txt (The text which is shown on a output screen)
Mymodel.h5 (H5 file is a file format to store structured data,  its not a model by itself)

GENDER
saved_model.pb
labelss.txt
Mymodel1.h5

Ethnicty
saved_model.pb
labelsss.txt
Mymodel2.h5


Usage :
Download my Repository
Open any Web Application Software and change directory to the folder where all the files are present.
Detecting Age_Gender_Ethnicity through Web Cam And Images
Run the python file(.ipynb,*) which is located in the repository
Note: The Images and all contents(Files/Folders) should be present in same folder where all the files are present

Press Ctrl + C to stop the program execution.

Output :

![Screenshot (108)1](https://github.com/jeetchheda0903/Age_Gender_Ethnicty_Detection/assets/96326553/c1d7dcc0-3016-4cc8-869b-dd9e3ccb6aa2)

![Screenshot (113)](https://github.com/jeetchheda0903/Age_Gender_Ethnicty_Detection/assets/96326553/c5e00be7-2ca9-4672-bf86-8eaaa4a9368c)

![Screenshot (113)1](https://github.com/jeetchheda0903/Age_Gender_Ethnicty_Detection/assets/96326553/c8e86f0e-b7c0-4f51-b92a-5ada6461b32d)
