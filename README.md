# Thesis_Project - Location Inference for Biodiversity Collections: Geocoding Specimen Records from Unstructured Text Using Transformer Models

📘 data_preparation.ipynb: data is prepared from raw json file and preprocess into an actionable df. Filtered out non reelvant clumsn and extracted fields from nested column dictionaries. Viusalization on a mpa of coordinates data points. Construction of pseudosentences. 

📘 s2_cells_development.ipynb: development of s2 cell partitioning given data points. annotation of cell to a specific record given its coordinates. visualize a record cell on a map. 

📘 s2_helpful_visuals.ipynb: visuals from S2 library helpful and included in the study. 

📘 encoding_to_hierarchical_labels.ipynb: convert cell id token to a hierarchical encoded representation. 

📘 model_finetuning.ipynb: custom dataset class. model goes thorugh training and is fine tuned to the specific task. 

📘 evaluation.ipynb: evaluation with metrics. Token Level Perturbation Analysis.  

