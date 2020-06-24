# Multimodal Analysis pipeline

Repository containing code and html report I generated during my master's internship at Providence St Joseph when performing multimodal analysis using Seurat on a library containing CITE-seq, scRNA-seq, TCR-seq and HTOs.

Preprocessing was done with 10x CellRanger pipeline as recommended by the vendor.

The post-processing was performed using Seurat3 as the backbone for QC and cleaning and then split into individual cases containing each hashtag (sample type): 

1. healthy donor PBMC
2. healthy donor PBMC stimulated
3. Head and Neck 
4. RCC (renal cell carcinoma)
5. NSCLC (non-squamous cell lung carcinoma)
