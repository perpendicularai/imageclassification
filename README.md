# Image Classification

This repo his been put together to showcase the ability of the using deep-learning to train an image classificaiton model. The model in particular has been trained to detect between real and fake faces. This is ideal for locations that require a high degree of security, whether it be banks, airports, government buildings, schools to name a few. The dataset used to train the model is 4GB is size. A link will be provided below. The model was trained for 100 epochs on an Intel i5 CPU with 8GB's of RAM, and thus can be deployed on most systems. 

## How to :
* Download dataset - `https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces`
*  Set train and test data paths in the notebook provided
* Once model has been trained, run the following command to save the model to be used for inference `model.save('MODEL_DIRECTORY_NAME')`. This will save all the model files to your current directory in the directory name you provided.

## Alternatively :
If you would like to get started right away with inference on an image. You may download the pretrained model. See below link -
`https://drive.google.com/drive/folders/1KNxjyd-FAB5TQ3KYUIU-w-3XtJs8c1QF` and use it in the inference section of the notebook.
