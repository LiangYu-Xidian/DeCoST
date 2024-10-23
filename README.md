## Unveiling Cell Type Heterogeneity in Spatial Transcriptomics based on Inter-domain Alignment and Gaussian Kernel Conditional Autoregressive (DeCoST model)
DeCoST utilizes inter-domain alignment and Gaussian kernel conditional autoregressive modeling, introducing cell type-specific expression matrices as prior information to accurately infer and separate
expression patterns of different cell types in spatial transcriptomic data. The method also employs domain adaptation techniques to reduce the dimensionality of sequencing data to a latent space, 
thereby addressing platform effects between different technologies. Furthermore, the coordinate information of spatial spots is considered and integrated into the conditional generation model using a Gaussian kernel function, 
aimed at enhancing the accuracy of spatial transcriptomic cell type identification.
## Tutorial
We provide the data used in the experiments of this article, using the MERFISH dataset as an example.  
* First, follow the steps outlined in the ___MERFISH_tutorial.rmd___ to process and obtain the ___cell_seurat_100.h5ad___ and ___st_seurat_100.h5ad___ files.  
* Second, use ___kmm_MERFISH_100.ipynb___ to generate the corresponding ___beta_100.csv___.
* Finally, continue executing the subsequent deconvolution operations as instructed in the ___MERFISH_tutorial.rmd___ to achieve the final results.

 __Note__: The numbers in the file names represent the bin size of the datasets used and should be adjusted according to the actual situations.












