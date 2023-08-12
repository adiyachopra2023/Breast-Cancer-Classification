# Breast-Cancer-Classification

## Types of Tumor

### 1. Benign Tumor
*	- Non-cancerous
*	- Capsulated
*	- Non-invasive
*	- Slow Growing
*	- Do not metastasize (spread) to other parts of the body
*	- Cells are normal
### 2. Malignant Tumor
*	- Cancerous
*	- Non-capsulated
*	- Fast Growing
*	- Metastasize (spread) to other parts of the body
*	- Cells have large, dark nuclei; may have abnormal shape

## Problem Statement: 
* To classify whether the existing tumor is benign or malignant. Malignant Tumors require immediate attention and treatment.

## Dataset: 
* The dataset is derived from a test known as Fine needle aspiration.
* {Fine needle aspiration is a type of biopsy procedure. In fine needle aspiration, a thin needle is inserted into an area of abnormal-appearing tissue or body fluid. As with other types of biopsies, the sample collected during fine needle aspiration can help make a diagnosis or rule out conditions such as cancer. Most fine needle aspirations are done on these areas:
*  - breast
*  - thyroid gland
* lymph nodes in the neck, groin, or armpit}

## Dataset Link: 
* https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

### Missing Values: None

## Attributes:
 
* ID
* Diagnosis (M or B) - M: Malignant, B: Benign

* Radius - mean of distances from center to points on the perimeter of each cell nucleus
* Texture - standard deviation of gray-scale values
* Perimeter 
* Area 
* Smoothness - local variation in radius lengths
* Compactness - (perimeter^2/area - 1.0)
* Concavity - severity of concave portions of the contour
* Concave Points - number of concave portions of the contour
* Symmetry 
* Fractal Dimension - (coastline approximation - 1)

* {Each of the above 10 attributes have a mean value, standard error value and a 'worst' or largest  (mean of the three largest values) of these features}

## Workflow:

1. Selecting dataset
2. Data Pre-Processing
3. Split data into train & test
4. Train ML model - Logistic Regression (binary classification)
5. Test the trained ML model


## References:
https://www.cancer.org/cancer/types/breast-cancer/screening-tests-and-early-detection/breast-biopsy/fine-needle-aspiration-biopsy-of-the-breast.html

Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
