![image](https://github.com/perpendicularai/imageclassification/assets/146530480/6938491a-8670-47a1-8cb8-aed6fcad5978)



# Image Classification

This repo his been put together to showcase the ability of the using deep-learning to train an image classification model. The model in particular has been trained to detect between real and fake faces. This is ideal for locations that require a high degree of security, whether it be banks, airports, government buildings, schools to name a few. The dataset used to train the model is 4GB's in size. A link is provided below. The model was trained for 100 epochs on an Intel i5 CPU with 8GB's of RAM, and thus can be deployed on most systems. 

## How to :
* Download dataset - [fakeface_dataset](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces)
*  Set train and test data paths in the notebook provided
* Once model has been trained, run the following command to save the model to be used for inference `model.save('MODEL_DIRECTORY_NAME')`. This will save all the model files to your current directory in the directory name you provided.
* A test image has been provided of someone that does not exist. The image was generated using a popular GAN. See [test_image](https://github.com/perpendicularai/imageclassification/tree/main/test_image/) directory for more.

## Alternatively :
If you would like to get started right away with inference on an image. You may download the pretrained model. See below link -
* [fakefacedetect_pretrained_model](https://drive.google.com/drive/folders/1KNxjyd-FAB5TQ3KYUIU-w-3XtJs8c1QF?usp=sharing) and use it in the inference section of the notebook.

## Training stats :
* Accuracy -
![image](https://github.com/perpendicularai/imageclassification/assets/146530480/df14fb83-568b-478b-8394-2022b3409818)

* Loss -
![image](https://github.com/perpendicularai/imageclassification/assets/146530480/743fbaf9-58a8-49e9-befe-9e3f32507597)


# A python program to detect face liveness in an image

## Usage :

### - pip install fakeface-detector

### - import fakefaceinf as ffi
### - res = ffi.predict_and_process_image('/path/to/your/image/jpg')
### - print(res)


## Important Notes

### - Please ensure that you create a directory called `models` to download and save the model from the following url : https://drive.google.com/drive/folders/1KNxjyd-FAB5TQ3KYUIU-w-3XtJs8c1QF and save it to the `models` directory. Without this step being being performed, the package will not work.

