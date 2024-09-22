# Dogs-vs-Cats-Classification
Project is to be able to classify an image on whether its a Dog or a Cat using Convolutional Neural Network(CNN)

Training and testing of the model is found in the **Jupyter-notebook file** while Gui app which uses the model to achieve the project objective is the **GuiApp.py**

The project uses [Keras](https://keras.io/) that is found in [Tensorflow](https://www.tensorflow.org/), with the latest version of _Tensorflow_, _Keras_ is found within in it, therefore installing _Tensorflow_, you will then have access to _Keras_

## Procedure of how to install Tensorflow and other dependecies in your jupyter notebook for this project is as follows
- Within you project folder, open a terminal/windows powershell and create a python virtual environment
  - to create a virtual environment:
  - run the commmand : **python -m venv name-of-your-virtual environment** remember to replace 'name-of-your-virtual environment' with the desired name you wish for your virtual environemt
  - activate the virtual environemt by running: **.\name-of-your-virtual environment\Scripts\activate**
- Install the needed libraries
  - install tensorflow by: **pip install tensorflow**
  - install pandas by: **pip install pandas**
  - install numpy by: **pip install numpy**
  - install matplotlib by: **pip install matplotlib**
  - Install all these libraries as they shall be used in the project, install them while in the virtual environment
- Install a python kernel to use for this project
    - run command **pip install ipykernel** to install ipykernel
    - run command  **python -m ipykernel install --user --name ML-kernel**   this creates a kernel with the name _ML-kernel_
- Open your jupyter notebook
- navigate to your project folder where we have the virtual environment
- click **new** and instead of choosing **Python3 kernel** choose the kernel we created , in our case its aclled **ML-kernel**
- Proceed with the project as tensorflow is found within your project folder
    
