# Frechet-regression
Codes for paper "Variable Screening and Spatial Smoothing in Fr\'echet Regression with Application to Diffusion Tensor Imaging".
## ultility_functions Folder
`dcov_rcpp.cpp`: rcpp file for computing distiance covariance\
`ultility.R` and `ultility_smooth.R`: contain functions to compute distance covariance and spatial smoothing\
`FRiSO`: part code of `FRiSO`, use to fit Fr\'echet rgression\
## var_sele Folder
`dc_sele_high_dim`: codes for variable screening using distance covariance\
`FRiSO_low_dim`: codes for variable selection using FRiSO\
## pred_error Folder
contains codes for computing matrix prediction error for data generated by spatial wishart process model 
