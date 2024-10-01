# DataCompressionCF
This folder contains the data and results from principal component analysis (PCA) and massive optimized parameter estimation and data compression (MOPED) in Wang etal (https://arxiv.org/abs/1910.09533).

# Data for isotropic analysis :

NS_Comb_zbin5.mono - measurment of correlation function monopole, xi_0(s)
Wang_etal_2016_COMBINEDDR12_covinv_s50to150_bin5.dat - fisher matrix of correlation function monopole 

# PCA results for isotropic analysis :

evalue_pre_zbin5.dat - eigenvalues
evec_pre_zbin5.dat - orthonormal eigenvectors {e_i(s), i=1,...,20}

# Data for anisotropic analysis :

pre_NS_zbin3_smu_2D_s25to150_mu20 - measurment of anisotropic correlation function, xi(s, mu)
cov_NT.dat - covariance matrix of xi(s, mu)

# PCA results for anisotropic analysis :

evalue_theory_NT.dat - eigenvalues
evec_theory_NT.dat - orthonormal eigenvectors {e_i, i=1,...,500}. The first ten eigenvectors are shown in Fig.7 in the paper. 

# PCA+MOPED results for anisotropic analysis :

weightalphaperp_evec_zbin3_smu500_s25to150_NT.dat 
weightalphapar_evec_zbin3_smu500_s25to150_NT.dat
weightbs8_evec_zbin3_smu500_s25to150_NT.dat
weightfs8_evec_zbin3_smu500_s25to150_NT.dat

which are the optimally weighted eigenvectors for {alpha_perp, alpha_{||}, bsigma_8, fsigma_8} parameters, respectively. The primary features for these parameters in two-point correlatin function are shown in Fig.8 in the paper.

New_full_Dweight_gamma_error_zbin3_smu500_s25to150_NT.dat - the weighted compressed coffecients in Eq.(14) in the paper
