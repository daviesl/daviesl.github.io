# Research



## Transport reversible jump proposals

Davies, L and Salomone, R and Sutton, M and Drovandi, C

Reversible jump Markov chain Monte Carlo (RJMCMC) proposals that achieve reasonable acceptance rates and mixing are notoriously difficult to design in most applications. Inspired by recent advances in deep neural network-based normalizing flows and density estimation, we demonstrate an approach to enhance the efficiency of RJMCMC sampling by performing transdimensional jumps involving reference distributions. In contrast to other RJMCMC proposals, the proposed method is the first to apply a non-linear transport-based approach to construct efficient proposals between models with complicated dependency structures. It is shown that, in the setting where exact transports are used, our RJMCMC proposals have the desirable property that the acceptance probability depends only on the model probabilities. Numerical experiments demonstrate the efficacy of the approach.

- [Published article](https://proceedings.mlr.press/v206/davies23a.html)
- [Code](https://github.com/daviesl/trjp)

ArXiv submission and slides for the [October 2022 Workshop on Statistical Deep Learning](https://andrewzm.github.io/deepspat-website/workshop/).

- [Preprint (arXiv)](https://arxiv.org/abs/2210.12572)
- [Workshop Slides](Laurence_Davies_Slides_TRJP_Oct_2022.pdf)
- [Poster (ADSN 2022)](TRJP_Poster_ADSN_2022.pdf)

Cite:
    @inproceedings{davies2023transport,
      title={Transport Reversible Jump Proposals},
      author={Davies, Laurence and Salomone, Robert and Sutton, Matthew and Drovandi, Chris},
      booktitle={International Conference on Artificial Intelligence and Statistics},
      pages={6839--6852},
      year={2023},
      organization={PMLR}
    }

## Bayesian detectability of induced polarization in airborne electromagnetic data

Davies, L and Ley-Cooper, AY and Sutton, M and Drovandi, C

Detection of induced polarization (IP) effects in airborne electromagnetic measurements does not yet have an established methodology. This work contributes a Bayesian approach to the IP detectability problem using decoupled transdimensional layered models and applies an approach novel to geophysics whereby transdimensional proposals are used within the embarrassingly parallelizable and robust sequential Monte Carlo class of algorithms for the simultaneous inference of parameters and models. This algorithm allows for adaptivity considerations for multiple models and proposal types. Methodological contributions to solid Earth geophysics include the decoupled layered model approach and proposal of a statistic that uses posterior model odds for IP detectability. A case study is included investigating the detectability of IP effects in airborne electromagnetic data at a broad scale.

- [Published article](https://academic.oup.com/gji/article/235/3/2499/7060381)

Cite:
    @article{davies2023bayesian,
      title={Bayesian detectability of induced polarization in airborne electromagnetic data},
      author={Davies, L and Ley-Cooper, AY and Sutton, M and Drovandi, C},
      journal={Geophysical Journal International},
      volume={235},
      number={3},
      pages={2499--2523},
      year={2023},
      publisher={Oxford University Press}
    }
