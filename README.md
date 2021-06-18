# cellRanger count

> cellranger-6.0.1/cellranger mkref refdata-gex-GRCh38-2020-A/fasta/genome.fa
> cellranger-6.0.1/cellranger count --id GA-p1 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample GA-p1 &
> cellranger-6.0.1/cellranger count --id GA-p2 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample GA-p2 &
> cellranger-6.0.1/cellranger count --id GA-p3 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample GA-p3 &

> cellranger-6.0.1/cellranger count --id normal-1 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample normal-1 &
> cellranger-6.0.1/cellranger count --id normal-2 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample normal-2 &
> cellranger-6.0.1/cellranger count --id normal-3 --transcriptome ../../refdata-gex-GRCh38-2020-A/ --fastqs . --sample normal-3 &
>

# Rscript 

> 1. count matrix processing.R
> 2. DEG analysis
> 3. cellphoneDB
