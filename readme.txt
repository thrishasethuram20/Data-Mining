Create an environment with aall the requirements satisfied
the code has bee run using Python 2.7
The flask app has been situated in the app.py file which is in CovidXrayPrediction_FlaskApp


Dataset has to be downloaded from 
https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia

test images are already in folder named test that has been uploaded to the repository
train folder should be having only images that are from covid, viral and normal folders.
Dataset folder has sub folders covid, viral and normal that can be downloaded from the link above.







cd D:\Project\COVID Detection form Chest X-ray Images
D:
conda activate major
jupyter notebook

goto cell option click on runall

copy generated resnet18-model.h5 file paste in flask app
---------------------------------------------------------------------------------------------------------
open anaconda prompt

cd D:\Project\COVID Detection form Chest X-ray Images\CovidXrayPrediction_FlaskApp
D:
conda activate major
python app.py

open crome and run the following url:
http://127.0.0.1:5000/




'C:\\Users\\nagas\\Downloads\\COVID-XRAY\\resnet18-model.h5'
