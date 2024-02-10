![image](https://github.com/perpendicularai/imageclassification/assets/146530480/6938491a-8670-47a1-8cb8-aed6fcad5978)



# Image Classification

This repo his been put together to showcase the ability of using deep-learning to train an image classification model. The model in particular has been trained to detect between real and fake faces. This is ideal for locations that require a high degree of security, whether it be banks, airports, government buildings, schools to name a few. The dataset used to train the model is 4GB's in size. A link is provided below. The model was trained for 100 epochs on an Intel i5 CPU with 8GB's of RAM, and thus can be deployed on most systems. 

## How to :
* Download dataset - [fakeface_dataset](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces)
*  Set train and test data paths in the notebook provided
* Once model has been trained, run the following command to save the model to be used for inference `model.save('MODEL_DIRECTORY_NAME')`. This will save all the model files to your current directory in the directory name you provided.
* A test image has been provided of someone that does not exist. The image was generated using a popular GAN. See [test_image](https://github.com/perpendicularai/imageclassification/tree/main/test_image/) directory for more.

## Alternatively :
If you would like to get started right away with inference on an image, see [PyPI_HOWTO.md](https://github.com/perpendicularai/imageclassification/blob/main/PyPI_HOWTO.md)

## Training stats :
* Accuracy -
![image](https://github.com/perpendicularai/imageclassification/assets/146530480/df14fb83-568b-478b-8394-2022b3409818)

* Loss -
![image](https://github.com/perpendicularai/imageclassification/assets/146530480/743fbaf9-58a8-49e9-befe-9e3f32507597)

