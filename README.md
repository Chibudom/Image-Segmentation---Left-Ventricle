** UNDER CONSTRUCTION**

# Image-Segmentation---Left-Ventricle
The purpose of the project is to develop a deep learning model capable of the automation of left ventricle heart masks extraction from Magnetic Resonance Imaging (MRI) data.

Data Collection: The dataset comprises MRI data from 44 patients. On average, about 10
MRI images were collected per patient. Each of these MRI images has been manually
segmented to highlight the left ventricle of the heart.

Model Training: The objective is to use this dataset to train a deep learning model. Given
an MRI image of a patient, the model will be designed to produce an image solely of the
left ventricle.

Post-processing: Following the model training, there will be a post-processing phase
which involves image refinement. Potential noise in the images will be eliminated, the
images will be normalized, and a collage will be created featuring the 10 most
representative images from each patient.

Further Application: This image collage will then be utilized to train another deep learning
model, the purpose of which is to detect cardiac diseases. By isolating and focusing on the
left ventricle, a crucial part of the heart, we aim to improve the effectiveness and accuracy
of Hypertrophic Cardiomyopathy (MCH) prediction.

Required Knowledge: Python, Deep Learning, Image Processing, Agility in Working with
Datasets, among others.

Evaluation metric: The Dice Coefficient is a widely used metric in the evaluation of image
segmentation quality in medical imaging. It's similar to the F1 score, but it's applied directly
to images. The Dice Coefficient is calculated as twice the area of overlap between the
generated mask and the real mask, divided by the sum of the areas of both masks.
