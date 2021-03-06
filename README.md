# Codes for ELG target selection for PFS Cosmology

The current version of the code relies highly on the EL-COSMOS catalog ([Saito et al. 2010](https://arxiv.org/abs/2003.06394)) as an input. 

Download the EL-COSMOS catalog from [this link](https://www.dropbox.com/s/i4vgpyet9nd9ryx/combinedcatalog_flux_SNR-cos_full_phy_fz-a0.20_OI15config_added-Re.fits?dl=0). Note that the catalog includes the signal-to-noise ratio of [OII] flux from PFS as well as the effective radius to compute the photometric error. 

Each source python code is independently developed. Currently in the repository you may find

- **summary_stat.py**

- **fisherlda.py**

- **add_photometryerror.py**
