# Scripts

Add your analysis scripts here, e.g.:

- `01_qc_trim.sh` — FastQC + trimming of raw reads
- `02_align_count.sh` — Alignment to *E. coli* K-12 MG1655 + read counting
- `03_deseq2_analysis.R` — DESeq2 differential expression, volcano/MA/heatmap plots
- `04_kegg_enrichment.R` — clusterProfiler KEGG enrichment for up/down gene sets

Keeping these in version control makes the whole analysis reproducible from raw FASTA/FASTQ files to the final figures and tables in `results/`.
