<div id = 'top'></div>

# RSNA-MICCAI-brain-tumor-radiogenomic-classification 🧠

*this was part of a 2021 Kaggle competition held by Radiological Society of North America which can be found <a href="https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification">Here</a>*
__________________________________________________________________________

## Project Abstract

```
The RSNA-MICCAI brain tumor radiogenomic classification challenge aimed to predict MGMT biomarker status in glioblastoma through binary classification on

Multi parameter mpMRI scans: T1w, T1wCE, T2w and FLAIR. The dataset is splitted into three main cohorts: training set, validation set which were used during

training , and the testing were only used during final evaluation. Images were either in a DICOM format or in png format. different architectures were used

to investigate the problem including the 3D version of Vision Transformer (ViT3D), ResNet50, Xception and EfficientNet-b3. AUC was used as the main

evaluation metric and the results showed an advantage for both the ViT3D and the Xception models achieving  0.6015 and 0.61745 respectively on the testing

set. compared to other results, our results proved to be valid given the complexity of the task. further improvements can be made through exploring

different strategies, different architectures and more diverse datasets.
```

## Main Architectures 
<div id="arch" align="center">
  
|Architecture|Image|
|--------------|-----|
|`ViT3D`|![ViT3D](https://github.com/MahmoudRabea13/RSNA-MICCAI-brain-tumor-radiogenomic-classification/blob/main/images/Vit-3d.png)|
|`ResNet50`|![ResNet](https://github.com/MahmoudRabea13/RSNA-MICCAI-brain-tumor-radiogenomic-classification/blob/main/images/ResNet50.png)|
|*`Xception`|![Xception](https://github.com/MahmoudRabea13/RSNA-MICCAI-brain-tumor-radiogenomic-classification/blob/main/images/image.png)|
|`EfficientNetB3`|![EfficientNetB3](https://github.com/MahmoudRabea13/RSNA-MICCAI-brain-tumor-radiogenomic-classification/blob/main/images/EfficientNet-B3.png)|

</div>

## Results 
<div id="results" align="center">
  
*The following table contains the best results obtained from each architectures* 
  
|Architecture|Validation AUC|Testing AUC|
|-----|-----|-----|
|`ViT3D`|0.5869|0.6015|
|`ResNet50`|0.42099|0.58078|
|***Xception**|***0.63827**|***0.61745**|
|`EfficientNetB3`|0.37407|0.55817|

</div>


<div id="team">
 
## Team Members

* [Amr Mohamed](https://github.com/Amrmohamed090)
* [Mahmoud Rabea](https://github.com/MahmoudRabea13)
* [Aya Sameh](https://github.com/Ayasameh1) 
* [Ehab Kamal](https://github.com/EHVB) 

</div>


## <a href="www.kaggle.com/competitions/rsna-miccai-brain-tumor-radiogenomic-classification/overview/acknowledgments">Acknowledgments</a>

```
The dataset for this challenge has been collected from institutions around the world as part of a decade-long project to advance the use of AI in brain tumor diagnosis and treatment, the Brain Tumor Segmentation (BraTS) challenge. Running in parallel with this challenge, a challenge addressing segmentation represents the culmination of this effort.

A comprehensive description of the both tasks of the RSNA-MICCAI Brain Tumor challenge can be found at: https://www.med.upenn.edu/cbica/brats2021/
Participants interested in the segmentation task of this competition can find more info at: https://www.synapse.org/brats2021
```


<p align="right"><a href="#top">Back to top</a></p>
