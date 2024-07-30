# A Genetic Programming Approach to Radiomic-based Feature Construction for Survival Prediction in Non-Small Cell Lung Cancer (source codes)

We provide MATLAB-based source codes that implement the genetic programming (GP) approach for feature construction, which has been applied to the two-year survival prediction in non-small cell lung cancer patients. 

This demo uses the LUNG1 dataset, which consists of 422 computer tomography scans publicly available at the Cancer Imaging Archive (https://www.cancerimagingarchive.net/collection/nsclc-radiomics). The PyRadiomics package (https://pyradiomics.readthedocs.io) was used to extract 105 classical radiomic features, including shape, volumetric, and texture features. These radiomic features are already provided in the "nsclc.mat" file.

The GP implementation uses the tree data structure for MATLAB, which is available at https://tinevez.github.io/matlab-tree/. We also provide these functions in the source codes. The codes were written in MATLAB 2022b.

The radiomic features represent the terminal set of the GP approach, while the function set is comprised by the arithmetic operators addition, subtraction, multiplication, and division, and also the minimum and maximum functions. The individuals in the population use a multi-tree representation to construct a multi-dimensional feature space.

Just download the "GP-radiomics.zip" file, uncomprees it, and run the "demo.m" file to perform an experiment.

![picture alt](https://github.com/wgomezf/GP-radiomics/blob/main/multi.png)
