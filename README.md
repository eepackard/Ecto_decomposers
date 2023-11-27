# Ecto_decomposers

Project aims to identify potential members of ectomycorrhizal decomposers guild and identify their niche in boreal forests. 

Two datasets are assessed:
- a regional dataset from a study designed to test spatial patterns of Mn-peroxidases and the fungal community compostion
- a national dataset subsetted from the Swedish Forest Soil Inventory.

The scripts should be run in the following order:

- clean_spatial_study_metadata.Rmd
- clean_taxonmicdata_SFSI_SS.Rmd
- clean_speciesdata_SFSI_SS.Rmd
- clean_filter_SFSI_soil_data.Rmd
- analysis_MnP_spatial_het.Rmd
- analysis_mnpdrivers.Rmd
- analysis_WAE.Rmd
- analysis_fungal_niche.Rmd
- analysis_genecounts.Rmd
- analysis_phylotree.Rmd
- create_sitemap.Rmd
- figures_fungal_niche.Rmd
