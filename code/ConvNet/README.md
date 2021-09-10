# Draw-a-Person ConvNet analysis scripts

Directory containing scripts to predict age-group and age-years from VGG19 feature vectors that Clint built off of Pablo's scripts  

## Prerequisites
Run in MacOS, using Colab to run more quickly
Prior versions tested on Linux/Debian distro.

Main libraries:
- Tensorflow 1.13.1
- Talos 0.4.9
- scikit-learn, scipy, seaborn, pandas, numpy  

## Scripts/Files

**The following scripts are updated and can be used as they are**:  

- ```ConvNet_VGG-19_Drawings_fc1.ipynb```: extraction of vector-features from DAP images taken from DAM study 1&3 kids and adult drawings using VGG-19 in the first fully connected layer
- ```ConvNet_VGG-19_Drawings_fc2.ipynb```: extraction of vector-features from DAP images taken from DAM study 1&3 kids and adult drawings using VGG-19 in the last fully connected layer
- ```ConvNet_VGG-19_Drawings_block5.ipynb```: extraction of vector-features from DAP images taken from DAM study 1&3 kids and adult drawings using VGG-19 in the last convolutional layer


- ```ConvNet_VGG_19_Drawings_305_Clint.ipynb```: early version of extraction of vector-features from (full sample) kids and adult drawings using VGG-19 in the last fully connected layer. 305 refers to the number of images which differed from the number that Pablo used.


## Usage
Run scripts locally by using **jupyter notebooks** or in the cloud with **google colab**  

