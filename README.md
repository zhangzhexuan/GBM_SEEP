# GBM_SEEP
GBM_SEEP (version 1) is a model for predicting seep-type brGDGTs in marine sediments using the fractional abundance of 15 brGDGTs. Related paper is accepted for publication in Limnology &amp; Oceanography.

Data 
-	globalbrgdgtlabel.csv contains the global brGDGT dataset for training the model. 
-	template.csv contains dataset (Sluijs et al., 2020) for making prediction.
- Yourdataset. csv is a template for your own dataset.

Code
-	GBM_SEEP.ipynb contains code with outputs shown related to our L&O paper.
-	NOTE that scores of the LightGBM-based model may depend on the version of the LightGBM package, version of Python, dependencies’ versions and CPU/GPU.
-	The code related to our L&O paper was tested on 4th December, 2022 using Google Colab (https://colab.research.google.com).
-	Simplified_GBM_SEEP.ipynb contains simplified code to make predictions using your own data.


If you want to apply the GBM_SEEP to your own dataset, please follow the steps below:
1.	Download the two .csv file (globalbrgdgtlabel.csv and Yourdataset.csv) and the simplified code (Simplified_GBM_SEEP.ipynb).
2.	Fill out the template file (Yourdataset. csv) using your own data. Please NOTE that summed fractional abundance of brGDGTs is 100 (IMPORTANT). Also NOTE that you should have a last column (e.g., depth or age). 
3.	Open the Google Colab. Then open the Simplified_GBM_SEEP.ipynb in the Google Colab.
4.	Upload Yourdataset.csv and globalbrgdgtlabel.csv into the main directory at left (Files/UploadFile).
5.	Just run all cells in Simplified_GBM_SEEP.ipynb! Then download the output files from the folder at left. Note that 0 represents marine-type brGDGTs, 1 represents seep-type brGDGTs, and 2 represents soil-type brGDGTs.
6.	Enjoy!


Reference: Sluijs A, Frieling J, Inglis G N, et al. Late Paleocene–early Eocene Arctic Ocean sea surface temperatures: reassessing biomarker paleothermometry at Lomonosov Ridge[J]. Climate of the Past, 2020, 16(6): 2381-2400.
