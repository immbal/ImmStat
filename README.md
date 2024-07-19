# ImmStat
Immune status biomarkers were identified from a top-down perspective for immunotherapy response prediction.

This repository includes the scripts and data of the proposed method.

- **feature_list.csv**: Gene interaction index list
- **features_top10_auc.rds**: Indicators AUC from different TME perspectives
- **cell_cell_envidences_details.csv**: Cellular interplay evidence
- **icb_cluster.rds**: Pan-cancer immunotherapy cohort cluster
- **pancaner_clinical.RDS**: Pan-cancer clinical information for TCGA
- **pancaner_expression.RDS**: Pan-cancer gene expression for TCGA
- **pancaner_ratio.RDS**: Gene interaction index for pan-cancer
- **pancaner_ratio_mean.RDS**: Mean of gene interaction index for pan-cancer
- **ICB_expression.tsv**: Pan-cancer immunotherapy gene expression
- **ICB_sample.tsv**: Pan-cancer immunotherapy cohort information
- **KIRC_GSE121636_CellMetainfo_table.tsv**: Cell metadata for KIRC_GSE121636
- **KIRC_GSE121636_expression.h5**: Single-cell expression for KIRC_GSE121636
- **KIRC_GSE121636_expression.zip**: Cell annotation for KIRC_GSE121636
- **SKCM_GSE120575_aPD1aCTLA4_Expression.zip**: Cell annotation for SKCM_GSE120575
- **NPC_GSE162025_Expression.zip**: Cell annotation for NPC_GSE162025
- **all_method_metrics.csv**: Model selection for immune status
- **model_aucs.csv**: Model benchmarks for all TME perspectives
- **ccpair_scores.csv**: CCPair scores with label
- **cell_fractions.csv**: Cell fractions with label
- **tf_activities.csv**: TF activities with label
- **tide.csv**: TIDE with label
- **immune_response_scores.csv**: Immune response scores with label
- **immune_status.csv**: Immune status with label
- **lrpair_weights.csv**: LRPair weights with label
- **pathway_activities.csv**: Pathway activities with label

- **the code.rmd**: Provides the code for data analysis and reproduction.
- **the anchor_genes.rmd**: Provides the code to explore anchor genes and their performance in relation to immune status.


