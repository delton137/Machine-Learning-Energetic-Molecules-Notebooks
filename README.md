# Machine Learning Energetics Python Jupyter Notebooks

License : MIT open source (see LICENSE file)

2017-2018 Daniel C. Elton

This repository contains Python Jupyter Notebooks to reproduce all of the results in our paper:

D. C. Elton, Z. Boukouvalas, M. S. Butrico, M. D. Fuge, and P. W. Chung, “[Applying machine learning techniques to predict the properties of energetic materials](https://www.nature.com/articles/s41598-018-27344-x#Sec24)”, *Scientific Reports* **8**, 9059 (2018).

notebooks are in "/notebooks/" and relevant data is in "/datasets/". Example .xyz coordinates generated for the Huang & Massa data are in /HM_all_xyz_files/ and .xyz coordinates for the Mathieu dataset are in /sensitivity_xyz

The code requires the *[Molecular Machine Learning Toolkit](https://github.com/delton137/mmltoolkit)*, which was developed in conjunction with the work in our paper.

There are a few bugs and orphaned code fragments in these notebooks, but the core functionality of these notebooks to reproduce figures, etc, has been tested. These notebooks are meant to be primarily used as a guide on how to work with the mmltoolkit.

If you use any of the code here, please cite our work. In addition to our *Scientific Reports* paper, you may also want to look at our follow up work, [“Machine Learning of Energetic Material Properties"](https://arxiv.org/abs/1807.06156).

## Data sources
Property data is publicly available and was taken from :

Huang, L. & Massa, L. Applications of energetic materials by a theoretical method (discover energetic materials by a
theoretical method). *Int. J. Ener. Mat. Chem. Prop.* **12**, 197–262 (2013)

and

Mathieu, D. Sensitivity of energetic materials: Theoretical relationships to detonation performance and molecular structure.
*Ind. & Eng. Chem. Res.* **56**, 8191–8201 (2017).

SMILES strings and .xyz coordinates were generated in house (see paper for details). 


