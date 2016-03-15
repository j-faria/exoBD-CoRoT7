## Uncovering the planets and stellar activity of CoRoT-7 <br/> using only radial velocities


This repository contains the data, code and results from the paper

*Uncovering the planets and stellar activity of CoRoT-7 using only radial velocities*  
J. P. Faria, R. D. Haywood, B. J. Brewer, P. Figueira, M. Oshagh, A. Santerne and N. C. Santos  
A&A, 588 (2016) A31, DOI: http://dx.doi.org/10.1051/0004-6361/201527899


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

    @article{Faria2016,
    author = {{Faria, J. P.} and {Haywood, R. D.} and {Brewer, B. J.} and {Figueira, P.} and {Oshagh, M.} and {Santerne, A.} and {Santos, N. C.}},
    title = {Uncovering the planets and stellar activity of CoRoT-7   using only radial velocities ⋆},
    DOI= "10.1051/0004-6361/201527899",
    url= "http://dx.doi.org/10.1051/0004-6361/201527899",
    journal = {A&A},
    year = 2016,
    volume = 588,
    pages = "A31",
    month = "",
    }



