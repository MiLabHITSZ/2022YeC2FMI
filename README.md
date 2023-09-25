# 2022-YeC2FMI
Implementation of Paper *"Z. Ye, W, Luo and M. L. Naseem, et. al., C2FMI: Corse-to-Fine Black-box Model Inversion Attack", TDSC, 2023.*

# Requirements

I have tested on:

- PyTorch 1.13.0
- CUDA 11.0


# The Simplest Implementation

### If you want to use our trained models, including styleGAN, target model, embedding model and inverse model (refer to Fig.4 in our paper):

1. dowloed `checkpoint` (both folder and files) from <https://huggingface.co/MiLab-HITSZ/C2FMI/tree/main>.
2. dowloed `trained_models` (both folder and files) from <https://huggingface.co/MiLab-HITSZ/C2FMI/tree/main>.

> python main_attack_antidefense.py

- note that you should create directory `gen_figures/DE_facescrub_mobile_M100_counter/` before running since our code does not automatically generate it.

### Or you can train your own models and change the models in script `main_attack_antidefense.py`.
