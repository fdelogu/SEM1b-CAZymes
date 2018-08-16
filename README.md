# SEM1b-CAZymes

This repo reproduces the computational analysis presented in the paper "From proteins to polysaccharides: lifestyle and genetic evolution of Coprothermobacter proteolyticus." (https://www.biorxiv.org/content/early/2018/07/11/280602).

## File structure

- CAZ_SEM1b.Rmd: Notebook to reproduce the analysis
- CAZ_SEM1b.html: Knitted version of the notebook, pictures and results are already generated
- Data\16Stimeseries_raw.txt: 16S amplicon read counts
- Data\CelluloseDegratation.txt: Cellulose utilization
- Data\ProteinConcentration.txt: Protein concentration
- Data\Sacch_table.txt: Saccharides quantification
- Data\caz_selected.txt: CAZymes annotated on the ORFs
- Data\caz_selected_ext.txt: CAZymes annotated on the gene groups
- Data\collapsed.mus: Transcript estimation for the gene groups
- Data\collapsed.uniques: Unique hits for the gene groups
- Data\not_collapsed.mus: Transcript estimation for the ORFs
- Data\not_collapsed.uniques: Unique hits for the ORFs
- Data\SpikeIn_counts\: RNA spike-in counts

## Notes
The code may be subject to small changes while transitioning to a more "tidy" style. Please be sure to install the required R and python libraries and to have an updated version of Rstudio (>=1.2.830).
