# VarientCallPipeline_nf
Simple variant call pipeline utilizing the Nextflow engine.

Steps:
    Fastqc - Quality control.
    BWA - Alignment.
    Samtools - Sort bam files.
    FreeBayes - Call varients.

Inputs:
    Directory containing paired end fastqc files.
    Reference file.
    Output directory.
