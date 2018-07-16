# Project Files
All files associated with this research project are cataloged here. Files which are too large to fit on the Github 
repo should be stored in [Synapse](www.synapse.org) and linked here.


## Non-local Files
- tcga_gtex_data.hd5
    - **syn12120302**  
    - TCGA and GTEx expression (TPM). `key=exp`
    - TCGA metadata. `key=tcga`
    - GTEx metadata. `key=gtex`
    - Combined metadata. `key=met`
    - Antineoplastic information: `key=drug`
    - Subtype pairing: `key=pairing`
- tcga-mc3-snvs-drivers.hdf
    - **syn12561067**
    - A comprehensive table of SNV mutation data from TCGA
 
## Local Files
Stored in a zipped file: **syn13854468**

### TCGA Driver Files
- Driver-Consensus-List.tsv
    - Gene consenus list
- Driver-Filtered-Samples.tsv
    - Sample, Subtype, Reason Removed
- Driver-MC3-Mutations.tsv
    - Gene, Transcript, Mutation
- Driver-Pathways.tsv
    - Gene, Subtype, Pathway
- Driver-False-Positive-Genes.tsv
    - True Positives, False Positives

### TCGA Pathway Files

- Tumor-Subtype-Mapping.tsv
    - Patient, Sample, Disease, Subtype — Maps Patient to Disease (acronym)
- Disease-Codes.tsv
    - Code, Description — Maps acronyms to disease
- Pathway-Cell-Cycle.tsv
- Pathway-HIPPO.tsv
- Pathway-MutSig-Genes.tsv
- Pathway-MYC.tsv
- Pathway-NOTCH.tsv
- Pathway-NRF2.tsv
- Pathway-PI3K.tsv
- Pathway-RTK-RAS.tsv
- Pathway-TGFBeta.tsv
- Pathway-TP53.tsv
- Pathway-WNT.tsv

### TCGA Alteration Matrices
- Alteration-Level.tsv
    - Samples by alterations (AMP/DEL/MUT/FUSION)
- Gene-Level.tsv
     - Samples by gene alteration (binary)
- Pathway-Level.tsv
    - Samples by pathway alteration (binary)

