# Machine Learning Projects

Proof of proficiency in machine learning concepts through various machine learning problems; leveraging python via TensorFlow, Features, Keras API Basics, Transfer Learning for Image Classification, Integrating Vision and Generative Models, etc.


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)


## Summary

This repository will be branched into three sections, "classification", "transfer", and "generative", which are described as follows.

1. Classification Exercise: movement of the exchange rate between the US dollar and the Canadian dollar in the next hour based on the previous hour's information for these securities. Note: the dataset and tf.records file used in this model can be retrieved on request, but are too large to attach here. The relevant files are: "createSavedDataset.ipynb", "customImputeLayerDefinition.ipynb", "buildAndTrainModel.ipynb", and "mySavedModel.zip".

2. Prototyping and Transfer Learning Exercise: detection of bird, squirrel and chipmunk presence; inference of bird type (of 358 types) from still images through two vision architectures classifying still images. Note: the dataset, tf.records files, and additional assets used in this model can be retrieved on request, but are too large to attach here. The relevant files are: "buildAndTrainBirdsVsSquirrels.ipynb", "preprocessDefinition.ipynb", "Preprocessing.ipynb", "birderModel.ipynb", and "saved_model.pb".

3. Integration of Vision and Generative Models: integrate a pipeling which, given a collection of natural images filters birds, squirrels and birdfeeders simultaneously; segments the resulting subsampled collection, inpaints squirrels to remove them, inpaints the bird to replace it with a bird of a different type, and develop a text query that produces images of a similar nature. Note: the dataset, tf.records files, and additional assets used in this model can be retrieved on request, but are too large to attach here. The relevant files are: "subSelectImages.ipynb", "segmentImages.ipynb", "removeSquirrels.ipynb", "collated.ipynb", "joinedForSquirrels.ipynb", and "saved_model.pb".

4. Generating Graph Connectivity: from a trained spiking neural network (SNN), using the notion of adjacency matrices, represent connectivity of neural network layers via graph networks. This won't be added to this repository until the associated publication goes out.

### Interface Notes:

All code was written using Python version 3.10.11 using Google's Colaboratory. Otherwise, code can be run via Jupyter Notebook.
