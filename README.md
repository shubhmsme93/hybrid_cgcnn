# Hybrid CGCNN: Graph Based Neural Network Model to Predict Total Energies of Known and Hypothetical Crystal Structures

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

To reporduce the models in our paper, following data can be downloaded
* [Total energies of ICSD structures from NRELMatDB databse](nrelmatdb_icsd_energies.csv)
* [Total energies of hypothetical structures](hypothetical_structure_energies.csv)
* ICSD crystal structures are not distributed as a part of ICSD license
* [Relaxed hypothetical crystal structures](relaxed_hypothetical_structures.tar.gz)

# Authors

* Shubham Pandey (shubhampandey@mines.edu)
* Peter St. John (Peter.STJohn@nrel.gov)
* Prashun Gorai (prashun.iitm4@gmail.com)

# License

This package is released under the MIT License.
