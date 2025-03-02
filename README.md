# Codes for the models developed in Sections 5.1 and 5.2 in the paper titled "A ZTF Search for Circumstellar Debris Transits in White Dwarfs: Six New Candidates, one with Gas Disk Emission, identified in a Novel Metric Space" by Bhattacharjee et al. 2025. ADS link: https://ui.adsabs.harvard.edu/abs/2025arXiv250205502B/abstract)

modelling_color_dependent_transit.ipynb -- This notebook contains the optically thin color-dependent dust extinction model developed in Section 5.1 in the paper. The notebook will reproduce Figures 10 and 11 in the paper.

gas_disk_model.ipynb -- This notebook contains the code for the optically thick gas disk emission model developed in Section 5.2 in paper. To examine the performance of this model and compare with the plots in the paper, we have included the Ca II emission line region from the LRIS spectrum used in the paper ("ca_data_new.csv") and the saved outputs from one MCMC run (the two ".npy" files).

melis.py -- Additional code snippet to solve for gas temperature using Melis+2010 equations. This code snipped can also be found inside gas_disk_model.ipynb.

Comments on the codes, their performance, and suggestion for any improvements are welcome. are welcome! If you are using (part of these) codes in your work, kindly cite the paper mentioned above. Any changes/corrections in the codes are welcome. If done so, the lead author of the paper would appreciate if contacted and informed (contact information below). Significant improvements can also be incorporated in the codes and the model can be made better.

Corresponding author: Soumyadeep Bhattacharjee 
Email: sbhatta2@caltech.edu
