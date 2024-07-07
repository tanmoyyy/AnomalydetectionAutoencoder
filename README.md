# AnomalydetectionAutoencoder
"This is a tutorial for anomaly detection with Autoencoder. The tutorial is based on 'Anomalies, Representations, and Self-Supervision' (arXiv:2301.04660). The aim here is to reproduce the upper left panel of Figure 1 from arXiv:2301.04660. Please first ensure that the necessary modules are installed. The notebook is created for a dataset provided as based on JHEP 05 (2019) 036, arXiv:1811.10276 (see also arXiv:2107.02157). The original training data can be found here: [https://zenodo.org/record/5046428](https://zenodo.org/record/5046428). The pp > A > 4l new physics (NP) samples are available at [https://zenodo.org/record/5046428](https://zenodo.org/record/5046428). Please utilize the 20k training samples for a less computationally intensive environment."

For inverse training, utilize Ato4l_inv.npy and background_inv.npy. Now the training should be done with the NP sampmes i.e. pp > A > 4l. Here the aim is to see the whether we can tag anomalous Standard Model events.   

For creating the representation utlize AnoCLR.ipynb. The augmentation and loss funtions can be found from the modules shared in [https://github.com/bmdillon/AnomalyCLR] .
