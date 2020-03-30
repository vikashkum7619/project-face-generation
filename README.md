# project-face-generation
 project-face-generation

In this project, i'll use generative adversarial networks to generate new images of faces.

Running using conda!
Run this in command line

Step 1: Create a new environment

conda create --name face-generation python=3
Step 2: Use the new env

source activate face-generation
Step 3: Install dependencies

pip install pillow
conda install -c conda-forge tensorflow=1.2.0
conda install -c conda-forge tqdm=4.11.2
conda install matplotlib scikit-learn jupyter notebook
Step 4: Open the notebook to run it

jupyter notebook dlnd_face_generation.ipynb
Project structure
This folder contains files for Udacity Deep Laerning Foundations Nanodegree Project 5: Face Generation.

dlnd_face_generation.ipynb - Main project file.

dlnd_face_generation.html - Face generation results file.

problem_unittests.py - Unit tests provided by Udacity.

helper.py - Help functions provided by Udacity.

data/simpsons/img_align_celeba/ - CelebA image datase.
