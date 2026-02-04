# CHIME: Molecule to Taxonomy ML Model

**Period:** 2024  
**Category:** Personal Project

---

**Active Demo available on [HuggingFace](https://huggingface.co/spaces/Guacamol/CHIME) !**

CHIME is an application that allows chemists to predict the taxonomic group of a compound based on its SMILES representation.

![CHIME](/assets/projects/CHIME/chime_app.png)

> This is a screenshot of the output of CHIME application when predicting the taxonomic group of Aflatoxin, a mycotoxin.

The application is based on a **SVM model** trained on *libsvm* with a dataset of 270k compounds.

The use of **SHAP values** allows to explain the model's predictions by highlighting the most important features in a similarity map of the compound.

This tool enable researchers to understand what features of a molecule a caracteristic of a taxonomic group, allowing them do better predict the structure of new compounds.

![Visualisations](/assets/projects/CHIME/mean_fingerprints_170_cool.png)

> This visualization was used during the early development of the model to understand the distribution of the features in the dataset.

