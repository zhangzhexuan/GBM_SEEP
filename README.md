# GBM_SEEP
GBM_SEEP (version 1) is a model for predicting seep-type brGDGTs in marine sediments using the fractional abundance of 15 brGDGTs. Related paper is accepted for publication in Limnology &amp; Oceanography.

Data 
-	globalbrgdgtlabel.csv contains the global brGDGT dataset for training the model. 
-	template.csv contains dataset (Sluijs et al., 2020) for making prediction.

Code
-	GBM_SEEP.ipynb contains code with outputs shown related to our L&O paper.
-	NOTE that scores of the LightGBM-based model may depend on the version of the LightGBM package, version of Python, dependencies’ versions and CPU/GPU.
-	The code related to our L&O paper was tested on 4th December, 2022 using Google Colab (https://colab.research.google.com).

Reference: Sluijs A, Frieling J, Inglis G N, et al. Late Paleocene–early Eocene Arctic Ocean sea surface temperatures: reassessing biomarker paleothermometry at Lomonosov Ridge[J]. Climate of the Past, 2020, 16(6): 2381-2400.
