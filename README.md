# encoding_model_tutorial
 
Tutorial on using LLM features to predict speech-evoked neural activity.
 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bootstrapbill/encoding_model_tutorial/blob/main/notebooks/encoding_tutorial.ipynb)
 
## Overview
 
This tutorial walks through building an **encoding model** that maps linguistic features — in this case large language model (LLM) embeddings — onto neural activity recorded with electrocorticography (ECoG) during natural speech listening.
 
You will learn to:
 
- Load and explore ECoG data and stimulus features from the Podcast dataset
- Construct delay-embedded feature matrices
- Fit encoding models via ridge regression
- Evaluate model performance and visualise predictions against recorded neural activity
 
The notebook is designed for interactive use in **Google Colab**. 
 
## Getting started
 
Click the **Open in Colab** badge above.
 
All data downloads and package installations are handled within the notebook itself — no local setup is required.
 
## Acknowledgements
 
This tutorial is adapted directly from the encoding notebook (`04-encoding.ipynb`) in the [Podcast ECoG Tutorials](https://github.com/hassonlab/podcast-ecog-tutorials) by the Hasson Lab at Princeton University.
 
The underlying dataset is described in:
 
> Zada, Z., Nastase, S.A., Aubrey, B., Jalon, I., Goldstein, A., Michelmann, S., Wang, H., Hasenfratz, L., Doyle, W., Friedman, D., Dugan, P., Melloni, L., Devore, S., Devinsky, O., Flinker, A., & Hasson, U. (2025). The "Podcast" ECoG dataset for modeling neural activity during natural language comprehension. *Scientific Data*, 12, 1135.
 
The dataset is freely available on [OpenNeuro](https://openneuro.org/datasets/ds005574) under a CC0 license.
