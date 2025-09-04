<h1 align="center" style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap;">
  
  Nonlinear system identification using modified variational autoencoders
</h1>


  <p align="center">
    <a href="https://scholar.google.com/citations?user=F1TZe1QAAAAJ&hl=es" target="_blank"><strong>Jose L. Paniagua<sup>1</sup></strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=7PIjh_MAAAAJ&hl=en" target="_blank"><strong>Jesús A. López<sup>1</sup></strong></a>
  </p>
  <p align="center">
      <strong><sup>1 </sup>UAO
      <strong><h4 align="center"><a href="https://www.sciencedirect.com/science/article/pii/S2667305324000206" target="_blank">Paper</a>
  </strong></p>

### Abstract
<p align="center">
    This research proposes a methodology for identifying nonlinear systems using input/output data and deep learning generative models. Our framework integrates Variational Autoencoders (VAE) with Nonlinear Autoregressive with exogenous input (NARX) in a unified identification structure to address overfitting in nonlinear system identification using NARX structures. Specifically, we modify a variational autoencoder by replacing the decoder module with a NARX model using the latent space information captured from the VAE encoder module as one of the exogenous inputs. Following the training phase, the decoder module can be used as a nonlinear model of the system. We evaluate the efficacy of our approach by performing open-loop prediction tests on data from four nonlinear benchmark systems: Cascaded tanks, Gas furnace, Silverbox, and Wiener-Hammerstein.
</p>



## Citation

If you find our code or paper useful, please cite
```bibtex
@article{PANIAGUA2024200344,
title = {Nonlinear system identification using modified variational autoencoders},
journal = {Intelligent Systems with Applications},
volume = {22},
pages = {200344},
year = {2024},
issn = {2667-3053},
doi = {https://doi.org/10.1016/j.iswa.2024.200344},
url = {https://www.sciencedirect.com/science/article/pii/S2667305324000206},
author = {Jose L. Paniagua and Jesús A. López},
keywords = {System identification, Deep learning, Generative modeling, Nonlinear dynamic systems},
}
```
