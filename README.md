# Animacy in German Folktales

This repository contains the reproducible code examples and analyses for the paper *"Animacy in German Folktales"* submitted in proceedings of CHR 2024: Computational Humanities Research Conference, 2024, Aarhus, Denmark.

**Authors:** Julian Häußler, Janis von Keitz, Evelyn Gius

**Institution:** *fortext lab, Technical University of Darmstadt, Germany*

**Reference:** Häußler, J., von Keitz, J., Gius, E. (2024). *Animacy in German Folktales*. CHR 2024: Computational Humanities Research Conference, December 4 – 6, 2024, Aarhus, Denmark. https://ceur-ws.org/Vol-3834/paper90.pdf.

**GitHub Repository:** https://github.com/forTEXT/Animacy_in_German_Folktales


## Repository Contents

- **[01 Preprocessing](animacy_in_german_folktales_01_preprocessing.ipynb)**
This notebook handles data preprocessing, including Processing CATMA exports and Calculating Inter-Annotator Agreement.

- **[02 Word Embedding Models](animacy_in_german_folktales_02_word_embedding_model.ipynb)**
Creating a Word2Vec model from the d-RomaneRomantik corpus (d-RoRo: Schumacher, M., Uglanova, I., & Gius, E. (2022). d-Romane-Romantik (d-RoRo) (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7223544)

- **[03 Classifier](animacy_in_german_folktales_03_classification.ipynb)**
Training and Validation of a classifier to identify animate entities in texts.

- **[04 Application Grimm](animacy_in_german_folktales_04_application_grimm.ipynb)**
Application of the trained animacy classifier to all Grimm's fairy tales. 

- **[05 Comparison Animacy Classification, NER, and POS](animacy_in_german_folktales_05_comparison_NER_POS.ipynb)**
A comparative analysis of animacy classification with Named Entity Recognition (NER) and Part-of-Speech (POS) tagging.

- **[06 Grimm NER+Evaluation](TODO: Link Notebook)**
Evaluation of NER models applied to Grimm's fairy tales. 


## Usage Instructions

1. Clone the repository:
   ```
   git clone https://github.com/forTEXT/animacy_in_german_folktales
   ```
2. Navigate to the cloned folder:
   ```
   cd animacy_in_german_folktales
   ```
3. Install required dependencies via the included *requirements.txt*. (For example using pip):
   ```
   pip install -r requirements.txt
   ```
4. Now you can run the notebooks. Further instructions if you want to reproduce the workflow with your own data can be found in the notebooks.  
