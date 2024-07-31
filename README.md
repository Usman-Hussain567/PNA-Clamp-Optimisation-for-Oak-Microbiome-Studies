This respository contains the script and data for creating the figures in the paper Hussain et. al 2024 (Link here - ).  

The "PNA_Clamp_Optimisation_Script.Rmd" contians the code for running the samples through the DADA2 pipeline to create ASVs, creating graphs from sequencing data and also the code to analyse and create graphs from the qPCR data.

The "Phyloseq_with_chloro_mito.RDS" contains a phyloseq object of sequencing data with chloroplast and mitochondria reads included. The phyloseq object contains an ASV table, classification table and the metadata. The "Phyloseq_exc_chloro_mito.RDS" is the same but filtering out all reads assigned to chloroplast and mitochondria ASVs.

The "qPCR_data.RDS" contains all data from qPCR along with the metadata.
