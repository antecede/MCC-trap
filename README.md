# MCC-trap
What is this repository for?

This repository contains all the necessary code and documentation for the Moth-trap software. It contains instructions and code for both training and data-processing.

How do I get set up?

Dependencies
The following dependencies must be installed.

Dependency	Version
scikit_image	tbd
numpy	tbd
scipy	tbd
Pympler	tbd
tensorflow	tbd
Pillow	tbd
PyQt5	tbd
OpenCV	tbd
Using Anaconda on Windows:
Install the dependencies and create the enviorement using the provided "env.txt" with the command "conda create --name myEnv --file env.txt"
Activate the enviorement using the command "activate myEnv"
Install opencv with the command "pip install opencv-contrib-python"
Start the program
Start the program by running the file idac_main.py with the command "python idac_main.py"

How do I train new models?
New models can be trained using the provided hp_param_training jupyter notebook script.

Edit the script before training, providing a data path, logging path, model save path and edit the steps per epoch.

Tensorboard command: tensorboard --logdir "LOG_PATH_HERE" --reload_multifile=true

Contribution guidelines
Comming soon.

Who do I talk to?
Jakob Bonde Nielsen or Kim Bjerge

Email: jakob.bonde.nielsen@gmail.com, kbe@ase.au.dk
