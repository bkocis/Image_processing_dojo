# Collection of image processing demo examples

## Requirements 
The demos require an installed package of openCV, and a webcam.
In case the examples are run from a virtual enviroment, in some occasions if the openCV library is installed from source, the python virtual environment need to gain acces to the cv2\*so files. This can be done by copying the cv2*.so file from the dist-packages to the site-packages folder of the virtual environment. For example:

`cp /usr/lib/python3.6/dist-packages/cv2.cpython-36m-aarch64-linux-gnu.so ~/your_virt_env_folder/YOUR_VIRT_ENV_NAME/lib/python3.6/site-packages/`


## Example scripts:
- Plant green area calculator 
  - detection of a defined HSV colour and calculate its area


