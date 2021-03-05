# feeding_freq_2021

The following repository can be used to recreate results presented in the following manuscript:
De La Guardia-Hidrogo VM, Paz HA, (2021). Influence of industry standard feeding frequencies on behavioral patterns and rumen and fecal bacterial communities in Holstein and Jersey cows. PLOS ONE. 16(3): e0248147. https://doi.org/10.1371/journal.pone.0248147

Analysis was done as follows: 
```
1. import_fastq.Rmd
2. qc_asvtable_deblur.Rmd
3. filter_phylotree_tax_rarefaction.Rmd
4. taxonomy.Rmd
5. alpha_metrics_rumen.Rmd
6. alpha_metrics_feces.Rmd
7. beta_metrics_rumen.Rmd
8. beta_metrics_feces.Rmd
9. beta_rumen_breed.Rmd
10. beta_feces_breed.Rmd
11. beta_plot_type_breed.Rmd
12. lefse_files.Rmd
13. diff_asv_heatmap.Rmd
```
Raw sequences are available at the NCBI Sequence Read Archive (SRA) under the accession no. SRP271418.
