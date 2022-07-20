#### Resnet Spectral Spatial ConvLstm: A means to extract features from Hyperspectral image
# Illustration
We combined 3DCNN with Batch Normalization with some shortcut 3D CNN connections, 2DCNN and LSTM models added and they helped to overcome all the challenges which are faced during exclusively and severally applying all the supervised models at the time of Hyperspectral image classification.




# Resnet Spectral Spatial ConvLstm Model
![](Finalone.JPG)
)
## Prerequisites
We have implemented this method on Google Colab. The version of Keras is 2.4.3, version of Python is 3.6.9 and version of Tensor flow is 2.3.1.
## How to run the code
* At first we need to import some libraries of Google credentials.
* After that we have to get the permission granted from the Gmail account to access any files from the Google Drive. Then we need to copy that generated link from the Gmail account and paste it on google colab.
* Each and every file has a unique id and that id can be obtained from google drive. If we want to have an access to a particular data set we
need to copy that id from google drive and subsequently paste it on google colab.
* In the next phase we have defined some functions like split of training testing ratio, dimension reduction technique and creating image cubes.
* After that we have to fix some hyperparameters namely window size; number of bands; training ratio and testing ratio.
* Afterwards we trained our ResnetConvLstm model.
* Finally we obtained the accuracy of our model and to visualize the predicted image and the ground truth image of that data set.
# DATA SOURCE
We got four different types of hyperspectral datasets namely Indian Pines, Pavia University, Botswana, and Kennedy Space Center
from the site: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes  
