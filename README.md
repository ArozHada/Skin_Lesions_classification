# Skin_Lesions_classification
Classification of the HAM-10000 dataset on skin lesions

**Challenge 1**
The binary problem of classifying Nevus images vs all
the others. We will give you 6000 images, 3000 being
nevus, 3000 being a combination of the others to train
the system. The test set will consist on 1015 images.

**Challenge 2**
A three-class problem consisting on the classification of
melanoma vs benign keratosis vs basal cell carcinoma.
The training set will consist on 1000 images for the first
two classes and 500 for the last one (imbalanced
problem). The test set consist on 226 images

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Pre-processing
Hair removal with black-hat transformation

![image](https://user-images.githubusercontent.com/19288227/179272642-89bb5f7d-1aaa-4842-a829-a8305a4c4e85.png)

--------------------------------------------------------------------------------------
## Features Extracted 
1. Hu moments
2. LBP
3. Color Histogram
4. HoG
5. GLCM
6. Haralick
7. SIFT

--------------------------------------------------------------------------------------
## Feature Engineering 
1. Data Normalization
2. PCA 

--------------------------------------------------------------------------------------
## ML Algorithms

![image](https://user-images.githubusercontent.com/19288227/179272946-7d01e1a9-869c-4fef-bf56-68152acc656e.png)

--------------------------------------------------------------------------------------
## Results

![image](https://user-images.githubusercontent.com/19288227/179273090-464681ba-7d00-4a72-9e5c-54ebf4fa8268.png)
