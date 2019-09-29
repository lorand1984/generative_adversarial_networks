# generative_adversarial_networks

This repository contains an example of a generative adversarial network used for generating images. 
 
## Projects
* [Face Generation](https://github.com/lorand1984/generative_adversarial_networks/tree/master/face_generator): Use a DCGAN on the CelebA dataset to generate images of new and realistic human faces.

## Installation
1. Clone the repository
2. Download the latest version of [miniconda](https://docs.conda.io/en/latest/miniconda.html) that matches your system.
3. Create and Activate a conda environment.
 - __Linux__ or __Mac__:
 ```
  conda create -n "your_folder_name" python=3.6
  source activate "your_env_name"
 ```
 -  __Windows__:
  ```
  conda create --name "your_folder_name" python=3.6
  activate "your_env_name"
 ```
4. From the conda environment, install PyTorch and torchvision.
 - __Linux__ or __Mac__:
```
conda install pytorch torchvision -c pytorch
```
 -  __Windows__:
 ```
conda install pytorch -c pytorch
pip install torchvision
```
5. Install other dependencies using pip (See requirements text file including opencv and jupyter notebook).
  ```
pip install -r requirements.txt
  ```



