# Stellar Classification 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ToOLoAHBy7jNSlc4TRXlLQpAQvCt_1w5?usp=sharing)

This repository contains a deep learning framework designed to classify stars based on their physical and photometric properties using the Harvard Spectral Classification system. The model addresses severe class imbalances through calculated inverse class weights and employs Linear Discriminant Analysis (LDA) for optimized dimensionality reduction. Model interpretability is analyzed using Shapley Additive Explanations (SHAP).


### Acknowledgements 

We would like to express our gratitude to Prof. Dr. A-Li Luo and Jun-Chao Liang, for providing the processed datasets, guidance, and the comprehensive catalog utilized in this study. 

The dataset and atmospheric parameter estimations (covering $T_{\text{eff}}$, $\log g$, $[\text{Fe/H}]$, and $[\alpha/\text{Fe}]$) for the LAMOST O-M-type stars used in this work are based on their spectral emulator framework. The official parameter catalog can be downloaded from the National Astronomical Data Center (NADC) via: [LAMOST O-M Stars Parameter Catalog (doi:10.12149/101402)](https://nadc.china-vo.org/res/r101402/)


```bibtex
@article{Liang2024ApJS,
  author        = {Jun-Chao Liang and A-Li Luo and Yin-Bi Li and Xiao-Xiao Ma and Shuo Li and Shu-Guo Ma and Hai-Ling Lu and Yun-Jin Zhang and Bing Du and Xiao Kong},
  title         = {{Estimating Stellar Atmospheric Parameters and [$\alpha$/Fe] for LAMOST O–M-type Stars Using a Spectral Emulator}},
  journal       = {The Astrophysical Journal Supplement Series},
  volume        = {275},
  number        = {1},
  pages         = {8},
  year          = {2024},
  month         = {nov},
  doi           = {10.3847/1538-4365/ad7505},
  url           = {[https://doi.org/10.3847/1538-4365/ad7505](https://doi.org/10.3847/1538-4365/ad7505)}
}
