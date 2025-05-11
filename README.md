# R-Cog_Imp_Prosody_VQ

This repo contains the full analyses for the paper **Al-Tamimi, J., Lofgren, M., Marquié, M., Rosende-Roca, M., Sanz, P., Tartari, J. P., Alegret, M., Sanabria, A., Ruiz, A., Boada, M., Valero, S., & Hinzen, W. (Under review). Automated prosodic and voice quality profiles across cognitive impairment. *Speech Communication*.**.

The following notebooks showcase the various types of analyses:
1. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_Summaries_correlations.nb.html) contains the summaries and correlation matrices
   
2. Classification results via Random Forests (RF)

   a. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_Classification5Categories.nb.html) contains the full RF analyses for the 78 combinations of models: 6 Types of Predictors (three acoustic and in combination with the cognitive) * 13 Types of Comparison

   b.  This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_Radar_charts_Pros_VQ_Neuro_sign_PIMP.nb.html) contains the radar charts for the most influential predictors identified via Random Forests using the PIMP approach
   
3. Multinomial Logit Regression (MLR)

   a. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_MultiLogRegProsody5CategoriesCovariates.nb.html) contains the MLR analyses for the 16 prosodic measures identified via PIMP, including pairwise comparisons with no corrections

   b. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_MultiLogRegProsody5CategoriesCovariates_Corr_Pair.nb.html) contains the MLR analyses for the 16 prosodic measures identified via PIMP, including pairwise comparisons with FDR corrections

   c. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_MultiLogRegVQ5CategoriesCovariates.nb.html) contains the MLR analyses for the 14 VQ measures identified via PIMP, including pairwise comparisons with no corrections 

   d. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_MultiLogRegVQ5CategoriesCovariates_Corr_Pair.nb.html) contains the MLR analyses for the 16 prosodic measures identified via PIMP, including pairwise comparisons with FDR corrections 

   e. This [notebook](https://jalalal-tamimi.github.io/R-Cog_Imp_Prosody_VQ/ACE_Radar_charts_Pros_VQ_sign.nb.html) contains the radar charts for each of the prosody, VQ or Prosody and VQ (in addition to the cognitive measures)

If reusing any material, make sure to cite the paper and this repository
