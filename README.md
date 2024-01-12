# Crime Hotspot Detection
This repository holds the code for my capstone project during my undergrad.

Link to published paper - https://link.springer.com/chapter/10.1007/978-981-99-3481-2_8

Link to the trained model - https://drive.google.com/drive/folders/1LWKzbMiV-Ix4Wsw0kIfpyNfjWFONH2WN?usp=sharing

**VISUALIZATION OF CRIME HOTSPOTS THROUGH ANALYSIS OF ONLINE NEWSPAPER ARTICLES**

**Description**

The aim of our project is to build a model which will utilize Natural Language Processing and Deep Learning to process publicly available data like newspaper articles from online sites to recognize the crime type and location where the crime was committed and build a corpus which can be visualized on a map.

To build the model the pre-trained BERT model has been used as the base.

we plan to extend the project in the future by adding connectivity to the database. The model can be extended to several cities/states based on availability of authentic and verified local newspaper in English.

**Installation**

the project can be run on the local system or Colab notebook service by Google.

Please follow the steps to setup the environment

*Local System*

- If your are not having the Jupyter notebook installed on your system visit https://jupyter.org/install.html and follow the necessary steps.

- Since we will be requiring CUDA  to run the model check if the GPU on your system will support CUDA. If CUDA is not supported please use Google Colab


*Google Colab*

- The first step is to create a Gmail account or sign-in to an existing account.
- Go to the following link https://colab.research.google.com/notebooks/intro.ipynb and select the File option and choose the New notebook option.
- Once you open the new notebook select the Edit option and choose the notebook settings. In the pop up that will appear select GPU in the dropdown box for the hardware accelerator option

**Requirements**

For the project you will require the following

- Libraries and Versions
  1. *huggingface-hub-0.0.8* 
  2. *pandas - 1.1.5*
  3. *numpy - 1.19.5*
  4. *torch - 1.8.1+cu101*
  5. *transformers - 4.6.0*
  6. *sacremoses-0.0.45*
  7. *tokenizers-0.10.2*
  8. *seqeval-1.2.2*
  9. *folium-0.8.3*
- Google API Key










