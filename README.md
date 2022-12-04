# GBM_SEEP
SEEP_GBM is a model for predicting seep-type brGDGTs in marine sediments using the fractional abundance of 15 brGDGTs. Related paper is currently under review in JGR-Biogeosciences.

Data 
-	CP.csv contains test dataset from Sluijs et al. (2020). This csv file is also a template for your own dataset. 
-	globalbrgdgtlabel.csv contains the global brGDGT dataset for training the model. 

Code
-	GBM_SEEP_JGR.ipynb contains code to reproduce the results in our manuscript
-	GBM_SEEP_simplified_application.ipynb contains simplified code to make predictions using your own data


If you want to apply the GBM_SEEP model to your own dataset, please follow the steps below:
1.	Download the two .csv file and GBM_SEEP_simplified_application.ipynb
2.	Replace the data in the template file (CP.csv) to your own data. Please NOTE that summed fractional abundance of brGDGTs is 100 (IMPORTANT). Also NOTE that you should have a last column (e.g., depth). 
3.	Open the Google Colab (https://colab.research.google.com). Then open the GBM_SEEP_simplified_application.ipynb in the Google Colab
4.	Upload CP.csv (replaced by your own data) and globalbrgdgtlabel.csv into the main directory at left (Files/UploadFile)
5.	Just run all cells in GBM_SEEP_simplified_application.ipynb! Then download the output files from the folder at left. Note that 0 represents marine-type brGDGTs, 1 represents seep-type brGDGTs, and 2 represents soil-type brGDGTs
6.	Enjoy!

Reference
Sluijs A, Frieling J, Inglis G N, et al. Late Paleocene–early Eocene Arctic Ocean sea surface temperatures: reassessing biomarker paleothermometry at Lomonosov Ridge[J]. Climate of the Past, 2020, 16(6): 2381-2400.
