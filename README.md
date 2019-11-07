## Dataset_S1.Smutans.tar.gz
31 Streptococcus mutans genomes reconstructed from metagenomic data

## Dataset_S2.Ssobrinus.tar.gz
315 Streptococcus sobrinus genomes reconstructed from metagenomic data

## Dataset_S3.SPARSE.tar.gz
|**Python Scripts** |      |
|----------------|------|
|1. SPARSE_ml.py   | Fit machine learning models on SPARSE results |
|2. SPARSE_curve.py| Calculate rarefaction curve on SPARSE results |
|3. SPARSE_dist.py | Calculate Euclidian distances of samples and species|
| | |
|**Source Files**  |      |
|1. SPARSE.species.profile| SPARSE results |
|2. SPARSE.samples| Oral sources of samples |
| | |
|**Batch workflow**| |
|1. commands.bash| All the commands to generate results |
| | |
|**Outputs**| |
|1. SPARSE.species.profile.SVM| Support Vector Machine results. Figure 2 |
|2. SPARSE.species.profile.PCA| PCA results. Figure S1 |
|3. SPARSE.species.profile.UMAP| UMAP results. Figures 1A & S1 |
|4. SPARSE.species.profile.curves| Rarefaction curves. Figure 5 |
|5. SPARSE.species.profile.sample.dist| Abundance distances of samples for NJ tree. Figure 1B |
|6. SPARSE.species.profile.taxon.dist| Abundance distances of species for NJ tree. Figures 4 & S2 |
