# Improving-EEG-Seizure-Detection-in-Newborns-through-Self-Distillation_UCC_AM6021
MSc Mathematical Modelling and Machine Learning Thesis Code Files (Appendix)

This repository contains 4 Jupyter notebooks, providing a step-by-step guide to developing a Neonatal EEG Seizure Detection Deep Learning Model using a 1D Convolutional Neural Network (CNN). The project implements an iterative pseudo-labelling method within a self-distillation framework to explore its effectiveness in improving neonatal EEG seizure detection, addressing label scarcity in neonatal EEG datasets.

### Contents:

1. **Preprocessing the EEG Data**
   - The notebook *EEG_Preprocess(compressed)* outlines the preprocessing steps for the neonatal EEG dataset from the Helsinki University Hospital. Outputs have been cleared to reduce file size.

2. **Building the Base and Ideal Models**
   - The notebook *EEG_Base_Ideal_model* explains the creation of the base/self-distillation model and an ideal model using the same 1D CNN architecture, along with their training and evaluation.

3. **Pseudo-Labelling with Confidence Thresholds**
   - The notebook *EEG_Pseudo_ConfidenceThreshold* details the iterative pseudo-labelling process, experimenting with classification-based selection criteria using confidence thresholds.

4. **Exploring Alternative Pseudo-Labelling Approaches**
   - The notebook *EEG_Pseudo_(CF_RejectedMethods)* explores confidence threshold and cumulative fixed percentage selection criteria, with reclassification, and discusses alternative pseudo-labelling approaches that were considered but not fully adopted for this project, laying groundwork for future research.
