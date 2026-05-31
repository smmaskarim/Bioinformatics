# Variant Calling

Germline and somatic variant calling were performed using the Genome Analysis Toolkit tools GATK HaplotypeCaller and GATK Mutect2, 
respectively.

## Germline variant calling: 
Performed on the normal sample BAM file using HaplotypeCaller.
## Somatic variant calling: 
Performed using paired tumor and matched normal BAM files with Mutect2 to identify tumor-specific variants.
