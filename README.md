# Bulk-RNA-seq-analysis
This is the code we used to submit articles.
  The R version (R version 4.0.2 (2020-06-22))is available on CRAN and https://www.r-project.org/. 

Analysis of the RNA-seq of ES, pES cells, ESC-PGCLCs, pESC-PGCLCs, E12.5 PGC and E9.5 PGC.
  The sequencing reads are demultiplexed using TrimGalore （https://github.com/FelixKrueger/TrimGalore） (v0.6.6). We use Hisat2 (v. 2.1.0) to align the reads to the mm10 reference genome. Transcript read counts calculated with featureCounts (v.1.5.2). From the resulting counts table, lowly expressed genes were filtered and library normalization was performed. The differential genes were used function in the Deseq2 package was applied to our dataset.Correlation analysis was used function in cor package.
