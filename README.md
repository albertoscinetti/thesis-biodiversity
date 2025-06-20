# Thesis Project
### Location Inference for Biodiversity Collections: Geocoding Specimen Records from Unstructured Text Using Transformer Models

------
This repository contains the code, data processing scripts, model configurations, and experimental results for my thesis project. The project investigates how to infer geographic coordinates for biodiversity specimen records by transforming tabular metadata into pseudo-sentences and training a fine-tuned transformer-based Seq2Seq model to predict hierarchical spatial cells.

------

#### Dataset 
The original data is obtained by Naturalis Biodiversity Center and contains around 3.5 million digital specimens objects. A partition of the data has been adopted for this reserach fo around 1 million records. Data is stored locally due to significant file size. 

-------

#### Code Structure 
The code is structured in relevant notebooks. A description of each notebook's content is given below. 

📘 data_preparation.ipynb: data is prepared from raw json file and preprocess into an actionable df. Filtered out non-relevant columns and extracted fields from nested column dictionaries. Visualisation on a map of coordinate data points. Construction of pseudosentences. 

📘 s2_cells_development.ipynb: development of s2 cell partitioning given data points. annotation of a cell to a specific record given its coordinates. Visualise a record cell on a map. 

📘 s2_helpful_visuals.ipynb: visuals from S2 library helpful and included in the study. 

📘 encoding_to_hierarchical_labels.ipynb: convert cell id token to a hierarchical encoded representation. 

📘 model_finetuning.ipynb: custom dataset class. The model goes through training and is fine-tuned to the specific task. 

📘 evaluation.ipynb: Evaluation with accuracy and hierarchical metrics. Token Level Perturbation Analysis.  

-----

#### Output Models 
Fine-tuned models have been stored locally due to significant file sizes. 

