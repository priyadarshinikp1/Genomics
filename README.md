# Genomics
Variant Calling Pipeline using GATK for SNPs, CNVs, SVs and Mt (mitochindrial variants)

gatk and picard were cloned from https://github.com/broadinstitute/gatk and https://github.com/broadinstitute/gatk respectively

#pipeline
1. preprocessing
2. indexing and aligning to reference genome
3. generating bam files
4. preprocessing bam files
5. marking duplicates
6. recalibrating quality
7. variant calling
8. annotation
