### Readme for "A statistical mechanics derivation and implementation of non-conservative phase field models for front propagation in elastic media" 
Authors: Travis Leadbetter, Prashant K. Purohit, Celia Reina 
Published in JMPS 2025

This repository contains the source code and raw data generated from simulations and used to produce the figures in the manuscript referenced above. If you encounter any problems with the code or data, please feel free to contact the first author at tjleadbetter04@gmail.com. 

#### File dependencies and structure. 
Source code is written in Python 3 using Jupyter Notebook (.ipynb). All code should run with just numpy, scipy, matplotlib, and [jax](https://docs.jax.dev/en/latest/quickstart.html). 

Fig. 1 is generated from STIVFreeEnergy.ipynb which produces three seperate plots (Fig1A.png, Fig1B.png, and Fig1C.png) corresponding to the panels in the manuscript. 

Fig. 2 is generated from QuarticFullCode.ipynb. The first part of the code can be used to generate new simulation data by altering the random number key or simulation inputs. The second half produces the figure from stored data named QuarticSimulationData.npz. 

Fig. 3 is generated from QuarticNonLinear.ipynb. The first part of the code can be used to generate new simulation data by altering the random number key or simulation inputs. The second half produces the figure from stored data named nonLinearQuartic.npz. 

Fig. 4 and Fig. 5 are generated from ProteinFullCode.ipymb. The first part of the code generates Fig. 4 from scatter data of the protein unraveling free energy originally gather by (Torres-Sanchez et al. 2019). A reproduction of this data is stored as protein_free_energy_data.npy. The middle part of the code can be used to generate new simulation data by altering the random number key or simulation inputs. The last part of the code produces Fig. 5 from stored data named realisticLargeFullProteinSimulationData.npy. 

Data used to produce Fig. 2, Fig. 3, Fig. 4, and Fig. 5 as shown in the manuscript will be made available upon request do to its large size. Please contact tleadbe1@sas.upenn.edu

#### References
Leadbetter, T., Purohit, P.K., Reina, C., "A statistical mechanics derivation and implementation of non-conservative phase field models for front propagation in elastic media." *JMPS* (2025). 

Torres-Sanchez, A., Vanegas, J.M., Purohit, P.K., and Arroyo, M., "Combined molecular/continuum modeling reveals the role of friction during fast unfolding of coiled-coil proteins." *Soft matter* 15.24 (2019): 4961-4975. 

