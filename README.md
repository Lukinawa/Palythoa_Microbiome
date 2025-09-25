# Palythoa_Microbiome
Analysis code for *Palythoa tuberculosa*  16S amplicon workflow (DADA2/phyloseq) and post-SymPortal ITS2 profiling, with ready-to-use plots


R code used in the *Palythoa tuberculosa* microbiome study:
- **16S Illumina pipeline** (QC → ASVs → stats/plots)
- **ITS2 SymPortal** downstream analysis (types & type profiles / DIVs)

## Quick start
- Run the 16S scripts in order (QC/denoise → taxonomy → decontam/phyloseq → diversity/stats → plots).
- For ITS2, load SymPortal exports and run the analysis/plot scripts.
- See script headers for any inputs and options.

## Requirements
R (≥ 4.5) with: `dada2`, `phyloseq`, `decontam`, `vegan`, `indicspecies`, `ggplot2`, `dplyr`, `tidyr`, `readr`, `scales`.

## Cite
SymPortal: Hume et al. 2019.  
DADA2: Callahan et al. 2016.  
phyloseq: McMurdie & Holmes 2013.

## License
MIT (feel free to reuse with attribution).
