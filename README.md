# InnoCyPES Summer School - Synthetic Smart Meter Data Generation using Variational Autoencoders

*Lecturer: Kutay Bölat*

This repo is dedicated to the demo notebook for InnoCyPES Summer School - Synthetic Smart Meter Data Generation using Variational Autoencoders tutorial. It contains the end-to-end training of a (modifiable) VAE. The dataset of choice is [Individual Household Electric Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption). The resolution of the smart meter readings is 60 minutes but can be decreased until 1 minute. Besides training, several visualizations are included at the end of the notebook: reconstruction and latent space.

## Running the notebook

### Colab 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kabolat/innocypes-summer-school_synthetic-data-tutorial/blob/master/vae_load_generation.ipynb)


If you run the notebook on Colab, you need to open a new cell and run `! pip install matplotlib==3.5.2` first. Other than this issue, the run on Colab should be seamless. However, in order to initiate a Tensorboard session, you need a (separate) terminal. If you are not a Colab Pro user, it is relatively hard (but not impossible) to use your local terminal. I advise you to either omit Tensorboard or run the notebook locally.


### Local
If you run the notebook on local, you can
- install all the libraries by hand,
- [use environment.yml](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) (for Conda), or
- [use requirements.txt](https://pip.pypa.io/en/stable/user_guide/#requirements-files) (for pip).


## Some references
[［1］](https://arxiv.org/abs/1312.6114) Kingma, D. P., & Welling, M. (2013). Auto-encoding variational bayes. arXiv preprint arXiv:1312.6114.

[［2］](https://openreview.net/forum?id=Sy2fzU9gl) Higgins, I., Matthey, L., Pal, A., Burgess, C., Glorot, X., Botvinick, M., ... & Lerchner, A. (2016). beta-vae: Learning basic visual concepts with a constrained variational framework.

[［3］](https://agustinus.kristia.de/techblog/2016/12/17/conditional-vae/) Kristiadi, Agustinus (2022). Conditional Variational Autoencoder: Intuition and Implementation. https://agustinus.kristia.de/techblog/2016/12/17/conditional-vae/

[［4］](https://ijdykeman.github.io/ml/2016/12/21/cvae.html) Dykeman, Isaac (2016). Conditional Variational Autoencoders. https://ijdykeman.github.io/ml/2016/12/21/cvae.html

[［5］](https://arxiv.org/abs/2110.11435)Wang, C., Sharifnia, E., Gao, Z., Tindemans, S. H., & Palensky, P. (2022). Generating multivariate load states using a conditional variational autoencoder. Electric Power Systems Research, 213, 108603.




