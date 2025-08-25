# On Integration of Vision and Generative Models

In this project a pipeline is integrated, which, given a collection of natural images, filters birds, squirrels and birdfeeders simultaneously; segments the resulting subsampled collection, inpaints squirrels to remove them, inpaints the bird to replace it with a bird of a different type, and develop a text query that produces images of a similar nature. Note: the dataset, tf.records files, and additional assets used in this model can be retrieved on request, but are too large to attach here. The relevant files are: "subSelectImages.ipynb", "segmentImages.ipynb", "removeSquirrels.ipynb", "collated.ipynb", "joinedForSquirrels.ipynb", and "saved_model1.pb".

All code was written using Python version 3.10.11 using Google's Colaboratory. Otherwise, code can be run via Jupyter Notebook. Both the Jupyter Notebook and Python files are included.

