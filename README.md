# CV-parking-space-detector

Visual surveillance of on-street parking spaces.

### Libraries used and versions:

- opencv_python=4.9.0.80
- matplotlib=3.8.0
- numpy=1.26.2
- scikit-image=0.20.0
- scikit-learn=1.2.2
- joblib=1.2.0

To run the code, make sure folder structure follows the format below:

root
|__407_Bejenariu_David_Cosmin_code.ipynb 
|__train
   |__Task1
      |__ground-truth-complete
      |__01_1.jpg
      |__...
   |__Task2
   |__...
|__test
|__model.joblib

You can opt for skipping the training cells and jump to the Test section where the pre-trained model is loaded (skip cells annotated with "[Can be skipped]"). In this case, there is no more need to include the "ground-truth-complete" folder.

Run each cell until "[Don't run these cells] Code for parking lots selection and model evaluation" markdown cell in sequential order. That should generate the results folder. 

Output is written to 'submission_files/407_Bejenariu_David_Cosmin'.

Overall runtime: 2 minutes.
