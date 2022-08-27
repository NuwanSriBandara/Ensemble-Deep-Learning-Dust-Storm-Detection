# Ensemble Deep Learning for Automated Dust Storm Detection using Satellite Images


**Paper Link [Will be added shortly]**

Abstract: 

>*Dust storms are considered a severe meteorological disaster, especially in arid and semi-arid regions, which is characterized by dust aerosol-filled air and strong winds across an extensive area. Every year, a large number of aerosols are released from dust storms into the atmosphere, manipulating a deleterious impact both on the environment and human lives. Even if an increasing emphasis is being placed on dust storms due to the rapid change in global climate in the last fifty years by utilizing the measurements from the moderate-resolution imaging spectroradiometer (MODIS), the possibility of utilizing MODIS true-color composite images for the task has not been sufficiently discussed yet. Here, a supervised ensemble learning approach comprising three state-of-the-art models is proposed to detect dust aerosols in the atmosphere of the Earth to test the above hypothesis. The proposed method incorporates a linear combination of U-Net, DeepLabv3+ and Swin U-Net as the deep learning architecture which quantifies a binary semantic segmentation problem of distinguishing dust-susceptible and nonsusceptible regions in each unconstrained MODIS image. The framework is tested upon a custom-developed dataset from MODIS measurements which contains 1020 true-color images, over land and ocean. The ground truth label for each image is manipulated through handcrafted binary segmentation which results in a binary ground truth image for each true-color MODIS image. The performance of the proposed framework is evaluated using mean Intersection-over-Union (mIoU) and average pixel accuracy (Acc) in terms of the semantic detection of dust aerosols. In the final testing, the framework has achieved its highest Acc of 87.3% with a mIoU of 75.2%. The obtained performance of the framework surpasses the single state-ofthe-art modalities and thus, aggregates to a more accurate implementation in the domain of dust aerosol detection*

<img src="https://github.com/NuwanSriBandara/Ensemble-Deep-Learning-Dust-Storm-Detection/blob/main/Figures/blockDiagram.png" width="1000"> <br />
Fig 1: Proposed Ensemble deep learning model - The proposed method consists of three DL models: U-Net, Deeplabv3+ and Swin U-Net as presented in
the figure. True-color RGB images in the dataset are resized into (256, 256, 3) and fed into all three base models to acquire the linearly combined ensemble
output for semantic dust storm segmentation

If you find this work, repository, or approach useful, please consider giving a star ⭐ and citation.

```
@article{nuwan_scse,
  author    = {Nuwan Sriyantha Bandara},
  title     = {Ensemble Deep Learning for Automated Dust Storm Detection using Satellite Images},
  journal   = {International Research Conference on Smart Computing and System Engineering - 2022},
  year      = {2022}
}

```

**Code will be released soon!!**
