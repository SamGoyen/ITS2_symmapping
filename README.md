## It uses Chris' SymPortal ITS2 alignment as a reference and counts aligned reads to each taxa and sums them by Genus and makes some nice plots.

### ITS2 Symbiont Profiling by Mapping Pipeline (Sym-Mapping)

This pipeline extracts ITS2 sequences from whole genome resequencing (WGS) or RNA-seq data and annotates them to the genus level based on similarity matching to ITS2 reference sequences from SymPortal (https://symportal.org/). This tool makes the most of non-targeted sequencing data and provides coarse-resolution symbiont information that can improve downstream analyses. Associated symbiont communities can be further resolved by using dedicated ITS2 sequencing analyses to derive ITS2 type profiles (e.g., using SymPortal)

See `ITS2_sym-mapping_pipeline.md` file for pipeline details and use.


---
For more information on symbiont typing with SymPortal, see the following resources:

Hume et al. 2019. SymPortal: A novel analytical framework and platform for coral algal symbiont next‐generation sequencing ITS2 profiling. _Molecular Ecology Resources_. 2019;19:1063–1080. https://doi.org/10.1111/1755-0998.13004

Github: https://github.com/reefgenomics/SymPortal_framework
