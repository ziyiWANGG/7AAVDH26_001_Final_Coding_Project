# 7AAVDH26_001_Final_Coding_Project
This project compares the denoising performance of DCT-based frequency domain filtering and Gaussian spatial domain filtering on low-dose brain CT images.

## Notebook
This notebook compares DCT-based denoising with Gaussian filtering for CT images.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ziyiWANGG/7AAVDH26_001_Final_Coding_Project/blob/a44bcddc3eba200e2dc22d8de7fd90ba14aa5532/CT_Denoising_DCT_vs_Gaussian.ipynb)

## Data source
The brain CT dataset used in this study is obtained from the PhysioNet repository:

Hssayeni, M. (2020). Computed Tomography Images for Intracranial Hemorrhage Detection and Segmentation (version 1.3.1). PhysioNet. https://physionet.org/content/ct-ich/1.3.1/

This dataset consists of head CT (Computed Tomography) images in jpg format. There are 2500 brain window images and 2500 bone window images, for 82 patients. There are approximately 30 image slices per patient. 318 images have associated intracranial image masks. Also included are csv files containing hemorrhage diagnosis data and patient data.
