# Shreya Bhagi

M.S. Bioinformatics student (thesis track) at Loyola University Chicago, graduating May 2027. I build pipelines that turn raw sequencing data into taxonomic and statistical results, mostly for metagenomics, and I build retrieval-augmented generation (RAG) applications in Python.

## Current research

**Sedimentary ancient DNA from Enos Lake** · M.S. thesis, Burns Lab

I analyze shotgun sedimentary ancient DNA (sedaDNA) from Holocene lake sediment cores to study how microbial and eukaryotic communities changed alongside climate over more than 10,000 years.

- Quality control and taxonomic classification with FastQC, MultiQC, Cutadapt, Kraken2 and Bracken, run with SLURM on Loyola's HPC cluster
- Abundance filtering, paleoclimate reconstruction (pastclim, terra, CHELSA-TraCE21k) and figures in R
- A Python workflow that extracts and summarizes eukaryotic records from Kraken2 output

The thesis is in progress, so its code and results are not public yet.

## Projects

| Project | What it is | Tools |
|---|---|---|
| [Compliance Evidence Assistant](https://github.com/shreyabhagi/compliance-evidence-assistant) | RAG application I built as a GenAI Developer Intern at MICROeAI, shared with the company's permission. It answers questions over uploaded compliance and clinical documents with inline citations, runs local LLMs through Ollama with ChromaDB retrieval, checks each answer against its sources, and has an automated test suite. | Python, Streamlit, Ollama, ChromaDB |
| [Prostate cancer risk modeling](https://github.com/shreyabhagi/ProstateCancerRisk_STAT408) | Regression analysis of a simulated dataset of 1,000 patient records: multiple linear and ordinal logistic regression, model diagnostics and AIC-based model selection, written as a reproducible Quarto report. | R, Quarto, ggplot2 |
| [*Lactobacillus* detection in urinary metagenomes](https://github.com/shreyabhagi/L.mulieris_L.jensenii_Project) | Four-person team project in the Putonti Lab screening public female urinary metagenomes from NCBI SRA for *L. mulieris* and *L. jensenii* with Sylph. This is my fork of the team repository; my contributions included a wrapper script with logging and per-sample error handling, and the reference-genome documentation. | Python, Sylph, SRA Toolkit |

## Other work

- **16S microbiome study (Burns Lab, 2024 to 2025):** compared eight commercial DNA extraction methods using DADA2 and phyloseq in R. Presented as a poster at Loyola's 2025 Undergraduate Research & Engagement Symposium.
- **Preprint:** co-author on a [bioRxiv preprint](https://doi.org/10.1101/2025.07.18.664790) on FOXA1 and SOX2 in therapy-resistant prostate cancer (2025), from wet-lab work with a lab partner engineering the FOXA1 R219C mutation.

## Skills

- **Languages:** Python, R, Bash
- **Metagenomics:** Kraken2, Bracken, DADA2, phyloseq, Sylph, FastQC, MultiQC, Cutadapt
- **Statistics and visualization:** regression modeling, alpha and beta diversity, ggplot2, tidyverse, Quarto
- **Computing:** Linux, SLURM, HPC, Git
- **Generative AI:** RAG, Ollama, ChromaDB, Streamlit
- **Learning now:** SQL

## Contact

Open to bioinformatics, computational biology, data science and generative AI roles across the U.S.: full-time now, or internships in 2027.

[LinkedIn](https://www.linkedin.com/in/shreyabhagi)
