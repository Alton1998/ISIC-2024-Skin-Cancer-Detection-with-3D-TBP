# ISIC 2024 - Skin Cancer Detection with 3D-TBP

## Abstract
In this paper we aim to develop an image based algorithm to identify histologically confirmed skin cancer cases with single lesion crops from 3D total body photos. The images used have come from close up images taken from a smartphone. These photos are often submitted for telehealth purposes.

## Introduction
[1] Melanaoma and Keratinocyte Skin Cancer(KSC) are the most common types od cancer in White Skinned populations. These tumor entities showed increasing incidence rates. Exposure to ultraviolet radiation(UV) radiation has been determined as the main risk factor for skin cancer. It is observed that there are more occurences of KSC which comprise of basal cell carcinoma(BCC) and squamous cell carcinoma(SCC).
BCC occurs due to intense UV exposure in childhood and adolescence. On the otherhand, SCC is caused due to chronic and cumulative UV exposure.

[2] Recent developement in dermoscope-based AI algorithms are shown to benefit clinicians in diagnosing melanoma, BCC and SCC. However, streamlining which individuals are at risk for these cancers and need clinician intervention is the main focus of this paper. Triaging application have a significant potential to benefit populations where healthcare infrastructure is strained.

## Stages of Work
Some stages of work that needs to be done in data cleaning:

1. Hair Removal.
2. Noise Removal.
3. Contrast Enhancement.
4. Resize

Do we consider segmentation and feature extraction?

Segmentation Strategies:
1. Edge based
2. Region Based 
3. Morphological
4. Active Contours
5. Histogram based Thresholds

Feature Extraction:

1. Asymmetry
2. Diameters
3. Compactness
4. Borders
5. Blue white veil.

Model training:

We first split the data into train data set and test dataset.

Some of the models to consider her are as follows:

1. ANN
2. CNN
3. KNN
4. GAN

Some metrics to consider:

1. Accuracy
2. Precision
3. Recall
4. F1 Score.

Our Aim would ideally be to reduce False negatives more than False Positives, so we would primarily focus on Recall and Specificity accordingly.


## Related Works

In [3] we have a survey of the related works. Some of the works are listed below:

Xie et al. proposes a skin lesion classification system into 2 main classes:

1. Benign
2. Malignant

The approach here uses something called as self generating neural networks. What this means is the neural network is generated automatically based on evaluation functions. Actions could include adding a neuron or removing a neuron or adding or removing connections based on evaluation functions. In the next phase the authors used PCA to perform dimensional reduction. The classification layer is compose of some ensemble neural networks. With a 


## Work Done

### Pre-processing
### Model Building
### Hyperparameter Tuning
## Results
## Conclusion

## References

[1] H. M. Gloster and D. G. Brodland, “The epidemiology of skin cancer,” Dermatologic Surgery, vol. 22, no. 3, pp. 217–226, Mar. 1996, doi: 10.1111/j.1524-4725.1996.tb00312.x.
[2] “ISIC 2024 - Skin Cancer Detection with 3D-TBP | Kaggle.” https://www.kaggle.com/competitions/isic-2024-challenge
[3] M. Dildar et al., “Skin Cancer Detection: A review using Deep learning techniques,” International Journal of Environmental  Research and Public Health/International Journal of Environmental Research and Public Health, vol. 18, no. 10, p. 5479, May 2021, doi: 10.3390/ijerph18105479.
