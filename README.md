# VanAllen_CTLA4_Science_RNASeq_TPM
Contains TPM matrices for pre-treatment samples from N = 42 ipilimumab-treated melanoma patients published in Van Allen et al. Science 2015 (Genomic correlates of response to CTLA-4 blockade in metastatic melanoma).

Matrix 1: TPM values generated via alignment with STAR (https://github.com/alexdobin/STAR) and quantification with RSEM https://deweylab.github.io/RSEM/README.html), using Gencode v19 (GRCh37) annotations. No further processing has been performed on these values. 

Matrix 2: TPM values generated via RNASeqQC, from de-duplicated BAMs (further information available in manuscript Supplementary Methods). Data is stored in .gct format (more info on file format available here: http://software.broadinstitute.org/cancer/software/genepattern/file-formats-guide#gct). 
