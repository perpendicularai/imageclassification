# A python package index module to detect face liveness in an image.
### This package is used in all of the face-recognition software that Perpendicular AI builds.

## Usage :
## Requirements
* `pip install fakefaceinf`

## Code
* `import fakefaceinf as ffi`
* `res = ffi.predict_and_process_image('/path/to/your/image/jpg')`
* `print(res)`


## Important Notes

#### - Please ensure that you create a directory called `models` in your project directory. Download and save the model from the following url : https://drive.google.com/drive/folders/1KNxjyd-FAB5TQ3KYUIU-w-3XtJs8c1QF (YOU'LL NEED A GOOGLE ACCOUNT) and save it to the `models` directory as `models\fakefacedetect`. Without this step being performed, the package will not work. 
