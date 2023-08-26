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

## Summary
A Convolutional Neural Network (CNN) architecture is proposed to combat major difficulties such as limited availability of data, overfitting, and computational complexity which are inherent to complex classification problems. The proposed approach utilizes a toy example of logo classification to evaluate the performance of the learning algorithm. The experimental framework employs an image dataset collected composed of 5933 total images. Techniques such as data augmentation, dropout, and transfer learning are applied to a test set composed of 80% of the images in the dataset while the remaining images were set aside for validation. Experimental results show that a CNN with complex data augmentation, the application of dropout, and transfer learning with EfficientNetB7 achieved an impressive 97.47% accuracy in correctly classifying the data on the validation set.

## Model Architecture
![CNNdiagram](https://github.com/jorgelalberto/Nocturna-Emblem-Classifier/assets/92881097/7fcd361b-c7ce-442d-bc89-f92c43a2a301)
Note: Applying Transfer Learning through EfficientNetB7 is shown to output a depth of 64. But this is only for display purposes, in actuality the depth is 2560.

by: David Langus Rodriguez, Jorge Luis Alberto, Rebecca G. Hart
