# Rubin-DES-Photometric-Calibration
This is a first attemp to construct a very minimalist photometric calibration linking DES and RUBIN

├── README.md               # Project overview + survey references  
├── requirements.txt        # Python dependencies  
├── data/                   # Placeholder for input catalogs (DES/Rubin/Gaia)  
├── notebooks/  
│   └── Rubin_DES_Calibration.ipynb  # Main analysis notebook  
└── scripts/  
    ├── crossmatch.py        # Cross-matching DES/Rubin with Gaia  
    └── photometric_fit.py   # Color-term fitting functions  


# Rubin-DES Photometric Cross-Calibration  
Template for comparing DES and Rubin (LSST) photometry using Gaia astrometry.

## Key Steps  
1. **Cross-match DES/Rubin catalogs** using Gaia DR3.  
2. **Fit photometric transformations** (zeropoints + color terms).  
3. **Validate with spatial residual maps**.  

## Surveys to Include  
- **DES DR2** (optical; `grizY`)  
- **Pan-STARRS DR2** (`grizy`; for u-band extension)  
- **Gaia DR3** (astrometric reference)  
- **VHS** (NIR; `YJHK`)  

## Usage  
