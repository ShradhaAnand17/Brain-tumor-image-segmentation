# Brain Tumor Segmentation using K-Means Clustering 🧠

## Overview  
This project applies **K-Means clustering**, an unsupervised machine learning method, to segment brain tumors from MRI scans. By grouping pixels based on intensity values, the approach separates potential tumor regions from surrounding brain tissue without relying on deep learning models.   
This project highlights how **classical ML + image processing** can support medical imaging tasks in cancer research.

## Features  
- 🧠 Tumor segmentation from MRI images  
- 🤖 K-Means clustering with scikit-learn  
- 🖼️ Input: MRI image → Output: clustered segmentation mask  
- 📊 Visual comparison of original vs. segmented image  

## Project Workflow  
1. Load MRI image  
2. Convert to NumPy pixel array (R,G,B,A)  
3. Apply **K-Means clustering (k=3)**  
4. Reconstruct segmented image from clusters  
5. Display **original vs. segmented result**  

## Tools & Libraries  
- **Python** – core programming language  
- **NumPy** – numerical operations & array handling  
- **Pandas** – dataframe manipulation (pixel data handling)  
- **Matplotlib** – visualization of original & segmented images  
- **PIL (Pillow)** – image loading & preprocessing  
- **scikit-learn** – KMeans clustering for segmentation  

## Learning Outcomes  
- Understanding how unsupervised machine learning (K-Means) applies to biomedical imaging  
- Building practical skills in clustering-based medical image segmentation  
- Exploring how AI techniques can be adapted for bioinformatics and healthcare research  

⚠️ Note: This project demonstrates segmentation on a **single MRI image**.  
Extending it to full datasets would require batch preprocessing, training loops, and larger computational resources.

