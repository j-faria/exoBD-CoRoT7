## Separating planets and stellar activity using radial velocities


This repository contains the data, code and results from the paper
_Separating planets and stellar activity using radial velocities_
by João P. Faria, Raphaëlle D. Haywood, Brendon J. Brewer, Pedro Figueira, Mahmoud Oshagh, Alexandre Santerne and Nuno C. Santos.


#### CoRoT-7 data

The HARPS radial-velocity observations are in the file [`corot7.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/corot7.txt)

#### birth-death MCMC

The code used to sample from the joint posterior distribution and calculate the evidence of the model can be found [here](https://github.com/eggplantbren/Exoplanet/tree/gp_quasiperiodic_noise)

Note that it is licensed under the GNU General Public Licence, version 3.

#### Input and Results

The input parameters and complete output analysed in the paper are available in this repository, in the following files:

- `OPTIONS`: the input option to DNest3
- `run.txt`: the log of the run
- `sample.txt`, `sample_info.txt`, `levels.txt`: step-by-step output with samples from the mixture of constrained priors and the diffusive nested smapling levels
- `posterior_sample.txt`: samples from the joint posterior distribution



## Attribution

If you use the code or results presented here, pleace cite the paper

    @article{faria+2015,
       author = {{Faria}, J.~P. and Haywood, R.~D. and Brewer, B.~J. and Figueira, P. and Oshagh, M. and Santerne, A. and Santos, N.~C.},
        title = {Separating planets and stellar activity using radial velocities},
      journal = {},
         year = 2015,
       eprint = {}
    }


