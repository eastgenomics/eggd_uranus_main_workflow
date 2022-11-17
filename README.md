# eggd_uranus_workflow (DNAnexus Platform Workflow)

DNAnexus Uranus workflow to support the Haem-Onc myeloid project

This workflow is a modified version of v1.9.1 (Novaseq) that is compatible with data produced by the Novaseq Instrument

---

## Current Version: 1.11.0

![Image of workflow](images/workflow.png)

## What apps are used in this workflow?

|  App 	| Version  	|
|---	|---	|
|multi_fastqc       |1.1.0|
|sentieon_bwa_mem   |3.2.0|
|sentieon_bam_to_vcf|3.2.0|_
|eggd_vcf_handler_for_uranus|2.6.1|
|cgppindel          |1.0.1|
|verifybamid        |2.1.0|
|picardqc           |1.0.0|
|samtools_flagstat  |1.0.0|
|mosdepth           |1.0.1|
|athena             |1.4.0|
|generate_vcf_metadata |1.0.0|
|somalier_extract   |1.0.2|
|sompy              |1.0.0|