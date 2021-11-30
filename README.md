# OcularToxicityQSAR

Repository for QSAR modeling

# Data files for transfer, currently stored at:

OcuTox_110321_FIN.xlsx : main data file, contains OCUTOXDB, modeling sets and main results

datasets.zip : OcuTox dataset matrices used as a starting point for modeling

ECHA_TEST_predictions_110321_FIN.xlsx : ECHA test set detailed results (including substances in overlap with OCUTOXDB)

ECHA_PROPS.xls : data file with descriptors and mapipng table for ECHA test set

ECHA1k_preds.zip : individual model predictions for ECHA test set

models-rds: R-objects (RDS files) of models

models-txt.zip : models auxuliary files - cross-validation predictions, etc

models_cv_consensus.zip : cross-validation consensus results for all the endpoints



# r-scripts_etc.zip : contains work scripts and some intermediate files
ocutox_110321.r : main script base, refers to other r files it needs, such as

xa.r

get_ad.r

qsar_eval.r

ocutox_dscr_lbl_mod.txt - descriptors list used for modeling

cas_mix.txt, cas_main.txt, 

echa1k_mix.txt, echa1k_main.txt : weighted feature matrices for modeling and prediction (can be recreated from main script)

