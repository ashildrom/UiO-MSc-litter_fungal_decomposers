# UiO-MSc-litter_fungal_decomposers

## Information: otu_table_mumu_curated_ashild.xlsx
### Methodological information
DNA extraction performed on 150 mg spruce litter per sample, PCR amplified and library prepared. Three libraries were paired-end sequenced using ITS2 at Fasteris, Switzerland. Returned raw sequences were demultiplexed using CUTADAPT, minimum overlap 26 bp, minimum read length 100 bp. Denoising and dereplicating sequences using DADA2, maximum two errors per read for both forward and reverse reads. ASV table produced and ITS2 region extracted using ITSx. ASV´s clustered into OTU´s using VSEARCH with a 97% sequence similarity threshold. Post-clustering performed using MUMU. Taxonomic annotation with a 0.8 certainty cut-off value using SINTAX.
### Data information
Column description:

OTU_id: unique OTU ID, Taxonomy: SINTAX taxonomy with certainty value at each taxonomic level, Taxonomy_cuttoff: SINTAX taxonomy with 0.8 certainty cut-off value, Abundance: sequence reads per OTU, S001-S288: sample ID.
## Information: otu_table_filtered_ashild.xlsx
### Methodological information
Filtered OTU table performed on otu_table_mumu_curated_ashild.xlsx. Non-fungal OTU´s, replicates and positive and negative controls removed. OTU´s removed if high abundance in negative control relative to biological samples. OTU´s from positive control removed. 
### Data information
Column description:

OTU_id: unique OTU ID, Taxonomy: SINTAX taxonomy with certainty value at each taxonomic level, Taxonomy_cuttoff: SINTAX taxonomy with 0.8 certainty cut-off value, OTUnumber: unique OTU number, Abundance: sequence reads per OTU, S002-S286: sample ID.
## Information: litterbags_sample_metadata.csv
### Methodological information

### Data information
Column description:

Sample_name: (site ID, management type, mesh type and subplot), Sample_ID_demultiplexing: sample ID, SITE_PAIR: site pair (1-10), PLOT_ID: plot ID (1-20), SUBPLOT: subplot (1-120), SITE_ID: name of site, MANAGEMENT: management type (CC, NN), MESH_TYPE: mesh type (L, S), locality_id: (site name, management type, subplot), 
## References


