## Uncovering the planets and stellar activity of CoRoT-7 <br/> using only radial velocities


This repository contains the data, code and results from the paper
_Uncovering the planets and stellar activity of CoRoT-7 using only radial velocities_
by João P. Faria, Raphaëlle D. Haywood, Brendon J. Brewer, Pedro Figueira, Mahmoud Oshagh, Alexandre Santerne and Nuno C. Santos. The article has been accepted for publication in section 10 of A&A.


#### CoRoT-7 data

The HARPS radial-velocity observations are in the file [`corot7.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/corot7.txt).

The observations were made with the HARPS spectrograph on the 3.6-m ESO telescope at La Silla Observatory, Chile.
The authors would like to acknowledge the many observers who contributed to the intensive observation campaigns.


#### birth-death MCMC

The code used to sample from the joint posterior distribution and calculate the evidence of the model can be found [here](https://github.com/eggplantbren/Exoplanet/tree/gp_quasiperiodic_noise)

Note that it is licensed under the GNU General Public Licence, version 3.

#### Input and Results

The input parameters and complete output analysed in the paper are available in this repository, in the following files:

- [`OPTIONS`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/OPTIONS.txt): the input option to DNest3
- [`run_log.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/run_log.txt): the log of the run
- [`sample.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/sample.txt), [`sample_info.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/sample_info.txt), [`levels.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/levels.txt): step-by-step output with samples from the mixture of constrained priors and the diffusive nested smapling levels
- [`posterior_sample.txt`](https://github.com/j-faria/exoBD-CoRoT7/blob/master/posterior_sample.txt): samples from the joint posterior distribution



## Attribution

If you use the code or results presented here, pleace cite the paper

    @ARTICLE{2016arXiv160107495F,
       author = {{Faria}, J.~P. and {Haywood}, R.~D. and {Brewer}, B.~J. and 
                 {Figueira}, P. and {Oshagh}, M. and {Santerne}, A. and {Santos}, N.~C.
                },
       title = "{Uncovering the planets and stellar activity of CoRoT-7 using only radial velocities}",
     journal = {ArXiv e-prints},
     archivePrefix = "arXiv",
      eprint = {1601.07495},
      primaryClass = "astro-ph.EP",
    keywords = {Astrophysics - Earth and Planetary Astrophysics},
        year = 2016,
       month = jan,
      adsurl = {http://adsabs.harvard.edu/abs/2016arXiv160107495F},
     adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }


