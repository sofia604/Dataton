## General info
This project is an analysis of the Ecuador exportations between 2017 and 2022, for the Devpost hackathon "Datathon TAWS 2022". You can check the hackathon details in: taws.devpost.com
	
## Technologies
Project is created with:
* Python version: 10
* Jupyter notebook
* Scikit-learn
	
## Description
The dataset analyzed contains the following information:
* DATE: Year and month of the exportation.
* SECTOR: Type of products exported.
* COUNTRY: Destiny country of the exportation.
* FOB: Value (in USD) of the shipped cargo, including custom fees.
* TONS: Weight of the products exported during that month.

In the notebooks folder you will find:
* data_analysis.ipynb: Preprocesing, grouping and visualization of the dataset information.
* models.ipynb: machine learning models for forecasting the FOB.
