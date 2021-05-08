# Hybrid Graph Neural Network for Total Energy Prediction

This package provides following utilities:
* Predict total energies of crystal strtuctures using a pre-trained model
* Train a model with a customized dataset

# Package Requirements

Follwoing python packages needs to be installed:
* [TensorFlow 2](https://www.tensorflow.org/install)
* [TensorFlow Addons](https://www.tensorflow.org/addons/overview)
* [pymatgen](https://pymatgen.org/installation.html)
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* [nfp](https://pypi.org/project/nfp/)

# Usage

* [Predict total energy using a pre-trained model](energy_prediction_demo)
* [Train a model using a customized dataset](train_model)
* [Pre-trained models](pretrained_models)

# Data

To reporduce the models in our paper, following data can be downloaded:

* *Total Energy*

  * [Total energies of ICSD structures from NRELMatDB databse (materials.nrel.gov)](nrelmatdb_icsd_energies.csv)
  * [Total energies of hypothetical structures](hypothetical_structure_energies.csv)

* *Crystal Structures*  

  * ICSD crystal structure files cannot be distributed 
  * [Relaxed hypothetical crystal structures](relaxed_hypothetical_structures.tar.gz)
  * [Unrelaxed hypothetical structures](unrelaxed_hypothetical_structures.tar.gz)

# Authors

* Shubham Pandey (shubhampandey@mines.edu)
* Peter St. John (Peter.STJohn@nrel.gov)
* Prashun Gorai (prashun.iitm4@gmail.com)

# Cite
"A Graph Neural Network for Predicting Energy and Stability of Known and Hypothetical Crystal Structures"

S. Pandey, J. Qu, V. Stevanovic, P. St. John, and P. Gorai, *ChemRxiv* (2021). DOI: [10.26434/chemrxiv.14428865.v1](https://doi.org/10.26434/chemrxiv.14428865.v1)

# License

This package is released under the MIT License.
