<div align="center">
    <a href="https://novoic.com" target="_blank"><img src="https://assets.novoic.com/logo_320px.png" alt="Novoic logo" width="160"/></a>
</div>

# Surfboard INTERSPEECH 2020

This is the repository sharing the code for the work done on the paper "Surfboard: Audio Feature Extraction for Modern Machine Learning" at INTERSPEECH 2020. The paper can be found [on arXiv](https://arxiv.org/abs/2005.08848). The Surfboard repository can be found [here](https://github.com/novoic/surfboard).

**Contents**
- `Comparison.ipynb`: Comparison of common features (local jitter, DDP jitter and local shimmer) between the Surfboard, OpenSMILE and Praat frameworks.
- `ParkinsonsClassification.ipynb`: Example classification task using Surfboard features, highlighting the importance of keeping train/test sets disjoint by participant and matching age/gender to create meaninful validation metrics.
- `ReferenceValues.ipynb`: Calculation of Surfboard reference means, medians, standard deviations and median absolute deviations on a 40-hour subset of LibriSpeech.