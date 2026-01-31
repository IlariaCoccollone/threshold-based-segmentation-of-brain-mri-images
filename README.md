# Threshold-Based Segmentation and Processing of Brain MRI Images
A medical image processing project focused on the segmentation and analysis of brain MRI images using threshold-based techniques.

## Abstract
This project explores threshold-based segmentation methods applied to brain MRI images, with the aim of isolating and analyzing anatomical structures. Starting from a T1-weighted brain MRI image from the BraTS 2020 dataset, the project implements a complete processing pipeline including preprocessing, thresholding techniques, post-processing, and result visualization. The work highlights the strengths and limitations of classical threshold-based approaches in medical image segmentation.

## File Structure 📁

1. **BraTS20_Training_012_t1.nii**  
   - T1-weighted brain MRI image from the BraTS 2020 dataset used as input for the segmentation experiments.  
   - Dataset source (Kaggle):  
     https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

2. **[BrainMRI_code.ipynb](./BrainMRI_code.ipynb)**  
   - Jupyter Notebook containing the full implementation of the threshold-based segmentation pipeline, including:
     - Intensity normalization and preprocessing  
     - Threshold-based segmentation methods  
     - Post-processing operations  
     - Visualization and quantitative analysis of results  

3. **[Threshold-Based-Segmentation-of-Brain-MRI-report.pdf](./Threshold-Based-Segmentation-of-Brain-MRI-report.pdf)**  
   - Final written report describing the theoretical background, methodology, experimental analysis, results, and conclusions of the project.

4. **[Threshold-Based-Segmentation-of-Brain-MRI.pptx](./Threshold-Based-Segmentation-of-Brain-MRI.pptx)**  
   - PowerPoint presentation summarizing the project objectives, segmentation techniques, experimental results, and main conclusions.

## How to Use the Project 🛠️

1. **Load the MRI Image**  
   Open the file `BraTS20_Training_012_t1.nii` and select the slice to be analyzed.

2. **Run the Segmentation Pipeline**  
   Execute the notebook `BrainMRI_code.ipynb` to perform preprocessing, apply threshold-based segmentation techniques, and visualize the results.

3. **Read the Final Report**  
   Consult `Threshold-Based-Segmentation-of-Brain-MRI-report.pdf` for a detailed explanation of the theoretical background, methodology, experimental analysis, and results.

4. **View the Presentation Slides**  
   Open `Threshold-Based-Segmentation-of-Brain-MRI.pptx` for a concise overview of the project objectives, methods, and conclusions.

## Authors 👩🏻‍💻👨🏻‍💻

- **Ilaria Coccollone** – i.coccollone@campus.unimib.it  
- **Andrea Matteo Re** – a.re25@campus.unimib.it
