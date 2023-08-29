# Description
YOLOv8 computer vision model designed to translate sign language alphabet characters into letters. Trained on data from me in my room!
Built using pytorch and ultralytic's YOLOv8 (You Only Look Once) classifier model. Samples were taken and videos analyzed using OpenCV's 
Python interface, and data was labeled using HumanSignal's labelImg software. Not completely refined due to training hardware constraints
and a small dataset, but mostly effective on most letters!

# Setup 
Install opencv-python via pip3 or homebrew (depending on platform), along with ultralytics. I used the following commands:
!pip3 install opencv-python
!pip3 install -U ultralytics --user

# Training
Install torch, torchvision, torchaudio appropriately for your machine from the instructions at https://pytorch.org/. Trained the model
using a GPU on a windows machine with CUDA enabled, recommend doing so to enable realistic training times. Code should be found in .ipynb file.

# Testing and Running Code
Last two cells of .ipynb file run the model on a training image, and allow for active sign language detection in another window. Run the 
code to use!
