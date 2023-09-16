Clark & Maguire 2023 Dataset

Downloaded and converted to BIDS by Ali Khan (ali.khan@uwo.ca)
2023/09/15

 - `clark_maguire_bidsify`:  snakemake workflows to download, merge 3d nii, and bidsify data
 - `bids_ses-1`: BIDS dataset for the first session (includes FLASH T1w, whole brain rs-fMRI, hippocampal rs-fMRI, MPM qMRI)
 - `bids_ses-2`: BIDS dataset for the second session (includes FLASH T1w, DWI, High-res T2w, manual subfields)


Note:
  - DWI is missing bval/bvec files
  - BIDS conversion for MPM data is pending
