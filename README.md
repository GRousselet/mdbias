Reproducibility package for the article:

**Reaction times and other skewed distributions: problems with the mean and the median**
Guillaume A. Rousselet & Rand R. Wilcox
[preprint](https://psyarxiv.com/3y54r/)
in press in [Meta-Psychology](https://open.lnu.se/index.php/metapsychology/index)

This repo contains only the code. Data and figures are available on [Figshare](https://figshare.com/articles/Reaction_times_and_other_skewed_distributions_problems_with_the_mean_and_the_median/6911924)

# Content

|folder|description|
|-----|-----|
|`code`|R `.Rmd` files to run simulations and create figures|
|`notebooks`|pdf versions of the code, with embedded figures|
|`data`|simulation results and FLP data needed to run the code|
|`figures`|all the figures used in the article, in pdf format|
|`functions`|extra R functions defined in text files|

# List of notebooks in the order of the article

|#|name|analyses|figures|
|-----|-----|-----|-----|
|1|`illustrate_bias`|effect of sample size on sampling distributions, bias estimation, bias correction|1, 4, 5|
|2|`miller1988`|replicate Miller 1988 + median bias + apply bias correction + detailed look at the effect of bias correction|2, 3, table 1|
|3|`samp_dist`|graphical representations of the sampling distributions of the mean and the median + SD + HDI|6, 7|
|4|`bias_diff`|group difference bias|8|
|5|`sim_gp_fp`|false positives for group comparisons of means, medians and deciles (shift function)|9, 10, 11|
|6|`sim_gp_g&h`|false and true positives simulations using g & h distributions: means, medians and 20% trimmed means|12, 13|
|7|`sim_gp_tp`|true positives for group comparisons of means, medians and deciles: uniform, spread, early, late differences|14, 15, 16|
|8|`flp_illustrate_dataset`|density plots of individual and group distributions of reaction times from French Lexicon Project|17, 18|
|9|`flp_bias_sim`|group difference bias in FLP data|19|
|10|`flp_sim_precision`|group level estimation accuracy using LFP data|20|
|11|`flp_exg_parameters`|fit ex-Gaussians to all conditions/participants|NA|
|12|`sim_gp_fp_flp`|simulation of group false positives using FLP data|21|
|13|`sim_gp_tp_flp`|simulation of group true positives using FLP data|22|
|14|`flp_dec_samp_dist`|individual and group shift functions|23|

# List of figures

|#|name| notebook|
|-----|-----|-----|
|1|`figure_illustrate_bias.pdf`|`illustrate_bias`|
|2|`figure_miller_distributions.pdf`|`miller1988`|
|3|`figure_miller_bias_summary.pdf`|`miller1998`|
|4|`figure_boot_md.pdf`|`illustrate_bias`|
|5|`figure_mdbc_examples_n10.pdf`|`illustrate_bias`|
|6|`figure_samp_dist_summary.pdf`|`samp_dist`|
|7|`figure_samp_dist_hdi_summary.pdf`|`samp_dist`|
|8|`figure_bias_diff_summary.pdf`|`bias_diff`|
|9|`figure_sim_gp_fp1_summary.pdf`|`sim_gp_fp`|
|10|`figure_sim_gp_fp2_part1.pdf`|`sim_gp_fp`|
|11|`figure_sim_gp_fp2_part2.pdf`|`sim_gp_fp`|
|12|`figure_gdist_sim.pdf`|`sim_gp_g&h`|
|13|`figure_hdist_sim.pdf`|`sim_gp_g&h`|
|14|`figure_sim_gp_tp_uni_summary.pdf`|`sim_gp_tp`|
|15|`figure_sim_gp_tp_early_summary.pdf`|`sim_gp_tp`|
|16|`figure_sim_gp_tp_tau_summary.pdf`|`sim_gp_tp`|
|17|`figure_flp_100.pdf`|`flp_illustrate_dataset`|
|18|`figure_flp_dist.pdf`|`flp_illustrate_dataset`|
|19|`figure_flp_sim.pdf`|`flp_bias_sim `|
|20|`figure_flp_sim_precision.pdf`|`flp_sim_precision`|
|21|`figure_gp_fp_flp_summary.pdf`|`sim_gp_fp_flp`|
|22|`figure_gp_tp_flp_summary.pdf`|`sim_gp_tp_flp`|
|23|`figure_flp_dec_samp_dist.pdf`|`flp_dec_samp_dist`|


