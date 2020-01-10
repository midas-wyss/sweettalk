# SweetTalk
Deep learning-based language model for glycan sequences

# Using Natural Language Processing to Learn the Grammar of Glycans

This repository provides code for Bojar et al. 2020.

# Abstract
While nucleic acids and proteins receive ample attention, progress on understanding the structural and functional roles of carbohydrates has lagged behind. Here, we develop a language model for glycans, SweetTalk, taking into account glycan connectivity and composition. We use this model to investigate motifs in glycan substructures, classify them according to their O-/N-linkage, and predict their immunogenicity with an accuracy of ~92%, opening up the potential for rational glycoengineering.

# Description
All data used for this project can be found in the Supplementary Tables associated with the linked manuscript. The annotated Jupyter notebook in this repository contains code used for model training & analysis, generating figures from the manuscript, and glycan masking & modification. Run the notebook in the provided order to avoid errors. Trained models can be found in the repository and, with helper functions, can be used to predict the immunogenicity of new user-defined glycan sequences and modify glycans to increase or decrease predicted immunogenicity.
