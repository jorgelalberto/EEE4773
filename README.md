# Final Project - Nocturna: Emblem Classifier

# Final Project

## The following files should be inside this zip folder:

  - `environment.yml` - to setup the conda environment
  - `experiments.ipynb` - the file in which we tested our models and decided on the best one
  - `training_functionipynb` - the file used to train and tune the hyperparameters of **Nocturna** our emblem classifier 
  - `NocturnaEmblemClassifierV3.h5` - our final exported model named **Nocturna** 
  - `test_function.ipynb` - in this file the test data can be loaded, please just input the file path in the `np.load('<FILE PATH>')` function
  - `test_hard_function.ipynb` - in this file the HARD test data can be loaded, please just input the file path in the `np.load('<FILE PATH>')` function
  - `nocturna_report.pdf` - this PDF explains the development of **Nocturna**, and the thinking process behind the emblem classifier 

## Model Architecture
![CNNdiagram](https://github.com/jorgelalberto/Nocturna-Emblem-Classifier/assets/92881097/7fcd361b-c7ce-442d-bc89-f92c43a2a301)
Note: Applying Transfer Learning through EfficientNetB7 is shown to output a depth of 64. But this is only for display purposes, in actuality the depth is 2560.

by: David Langus Rodriguez, Jorge Luis Alberto, Rebecca G. Hart
