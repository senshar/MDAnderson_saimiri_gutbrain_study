# AmatoLab_saimiri_shotgun
Code and data for squirrel monkey manuscript in prep for BMC Bio.

1. 16S_qiime - has scripts for analysis done in qiime to get ASVs
2. shotgun_bioinformatics - has scripts for profiling metagenomic data using HUMAnN3.9
3. Sen_et_al_BMC_Bio_MS - scripts for statistical analsyis and producing plots for BMC Bio manuscript
4. Datasets
 -   4.1. shotgun_metadata.RDS: contains metadata and outcome variables of interest
   
    -  "Sample"
    -  "Location"
    -  "Animal"
    -  "Name"
    -  "Species"
    -  "Sex"
    -  "Age"
    -  "Date_Birth"           
    - "Last_Weight"
    - "Last_Weight_Date"
    - "Exemption"
    - "Location_Type"
    - "Age_Group"
    - "Age_group1"
    - "otu_samplename"
    - "enclosure"            
    - "dod"
    - "status"
    - "time"
    - "num_reads"
    - "shannon"
    - "simpson"
    - "observed_pathways"
    - "observed_pathways_new"
    - "otu_shannon"          
    - "otu_richness"
    - "otu_PC1"
    - "otu_PC2"
    - "otu_PC3"
    - "acetate"
    - "butyrate"
    - "propionate"
    - "valerate"             
    - "otu_PC1_cat"
    - "asv_reads"
    - "shotgun_BC_PCoA1"
    - "shotgun_atc_PCoA1"
    - "shotgun_BC_PCoA2"
    - "shotgun_atc_PCoA2"
    - "otu_faith"
    - "total_SCFA"           
    - "asv_log_reads"

     
- 4.2 sbol16S_ps_without_contam_before_filtering.rds: phyloseq object containing taxonomy, feature table, and sample metadata
- 4.3 sbol_filtered_pathway_dataJul12026.rds: filtered functional pathway table.
- 4.4 sbol_metab_pareto: filtered, log transformed, pareto scaled metabolite matrix
- 4.5 sbol_gbm_data_for_maaslin3_Aug10.rds: gut brain modules functional pathway
- 4.6 sbol_GBM_metadata_maaslin_Aug112926.RDS: metadata for maaslin analyses for GBMs
- 4.7 limma_metab_metadata_for_metabolites.csv: metadata for limma anlayses for metabolites
