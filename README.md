For each folder, e.g., embryogenesis, run the code in the following order:
1. prepare_data.Rmd (this downloads the data)
2. run_corgi.Rmd
2. rank_genes.Rmd
3. prepare_gene_sets.Rmd

The remaining can be ran in any order. The following relates the figures in the paper to the code.

# Figures in the main paper

Figure 2 => embryogenesis/figures_main.Rmd

Figure 3 => neurogenesis/figures_main.Rmd

Figure 4 => cardiogenesis/figures_main.Rmd

# Figures in the Supplementary Information

Figure S1 => embryogenesis/figures_supp_pca.Rmd

Figure S2 => embryogenesis/figures_supp_cca.Rmd

Figure S3 => embryogenesis/figures_supp_mnnpca.Rmd

Figure S4 => embryogenesis/figures_supp_mds_hdg500.Rmd

Figure S5 => embryogenesis/figures_supp_hvg.Rmd

Figure S6 and S7 => embryogenesis/figures_supp_venn_diagram.Rmd

Figure S8 => cardiogenesis/figures_supp_replicates.Rmd


# Gene list

Supplementary Information Section 4.1 - => embryogenesis/table_gene_sets.Rmd

Supplementary Information Section 4.2 - => neurogenesis/table_gene_sets.Rmd

Supplementary Information Section 4.3 - => cardiogenesis/table_gene_sets.Rmd
