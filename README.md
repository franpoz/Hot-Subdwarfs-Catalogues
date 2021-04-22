# Hot Subdwarfs Catalogues (Van Grootel et al. 2021)

Status: Submitted to A&A (20-01-2021) # Accepted (14-04-2021)\
Accepted Version: [Van_Grootel_2021.pdf](https://github.com/franpoz/Hot-Subdwarfs-Catalogues/tree/main/Van_Grootel_accepted_version.pdf) 

On-line repository: [NASA/ADS](https://ui.adsabs.harvard.edu/abs/2021arXiv210410462V/abstract)


## A transit survey to search for planets around hot subdwarfs: I. methods and performance tests on light curves from Kepler, K2,TESS, and CHEOPS.

### Abstract
_Context_. Hot subdwarfs experienced strong mass loss on the Red Giant Branch (RGB) and are now hot and small He-burning objects. Such stars constitute excellent opportunities to address the question of the evolution of exoplanetary systems directly after the RGB phase of evolution.\
_Aims_. In this project we aim to perform a transit survey in all available light curves of hot subdwarfs from space-based telescopes (Kepler, K2, TESS, and CHEOPS), with our custom-made pipeline SHERLOCK, in order to determine the occurrence rate of planets around these stars, as a function of orbital period and planetary radius. We also aim to determine whether planets previously engulfed in the envelope of their red giant host star can survive, even partially, as a planetary remnant.\
_Methods_. In this first paper, we perform injection-and-recovery tests of synthetic transits for a selection of representative Kepler, K2 and TESS light curves, to determine which transiting bodies, in terms of object radius and orbital period, we will be able to detect with our tools. We also provide such estimates for CHEOPS data, which we analyze with the {\tt{pycheops}} package.\
_Results_.Transiting objects with a radius <=1.0 R_Earth can be detected in most of Kepler, K2 and CHEOPS targets for the shortest orbital periods (1 d and below), reaching values as small as ~0.3 R_Earth in the best cases. Reaching sub-Earth-sized bodies is achieved only for the brightest  TESS targets, and the ones observed during a significant number of sectors. We also give a series of representative results for farther and bigger planets, for which the performances strongly depend on the target magnitude, the length and the quality of the data.\
_Conclusions_.The TESS sample will provide the most important statistics for the global aim of measuring the planet occurrence rate around hot subdwarfs. The Kepler, K2 and CHEOPS data will allow us to search for planetary remnants, i.e. very close and small (possibly disintegrating) objects, which would have partly survived the engulfment in their red giant host.


<p align="center">
  <img width="110%" src="/images/histo_colormap.png">
</p>

_Fig 1. Number of hot subdwarfs observed by Kepler, K2, TESS (primary mission), and CHEOPS (as of November 19, 2020) per G magnitude bin._



<p align="center">
  <img width="100%" src="/images/celestial_full.png">
</p>

_Fig 2. Celestial distribution of hot subdwarfs observed by TESS primary mission (blue points), TESS extended mission in 2-min cadence (red points) and  TESS extended mission in 20-s candence (orange points), Kepler (purple crosses), K2 (black triangles) and CHEOPS (green stars)._


The catalogues themselves can be found in the [TESS](https://github.com/franpoz/Hot-Subdwarfs-Catalogues/tree/main/TESS), [Kepler & K2](https://github.com/franpoz/Hot-Subdwarfs-Catalogues/tree/main/Kepler_K2), and [CHEOPS](https://github.com/franpoz/Hot-Subdwarfs-Catalogues/tree/main/CHEOPS) folders in this repository in excel format.



### Some of the packages used in this work

[The SHERLOCK PIPEline](https://github.com/franpoz/SHERLOCK)

[Pycheops](https://github.com/pmaxted/pycheops)

[Matplotlib](https://github.com/matplotlib/matplotlib)

[Transit Least Squares](https://github.com/hippke/tls)


### Citation

The catalogues presented in this repository are public. Please, consider to cite Van Grootel et al. (2021) if you use them in your reseach.
```
@ARTICLE{2021arXiv210410462V,
       author = {{Van Grootel}, V. and {Pozuelos}, F.~J. and {Thuillier}, A. and {Charpinet}, S. and {Delrez}, L. and {Beck}, M. and {Fortier}, A. and {Hoyer}, S. and {Sousa}, S.~G. and {Barlow}, B.~N. and {Billot}, N. and {D{\'e}vora-Pajares}, M. and {{\O}stensen}, R.~H. and {Alibert}, Y. and {Alonso}, R. and {Anglada Escud{\'e}}, G. and {Asquier}, J. and {Barrado}, D. and {Barros}, S.~C.~C. and {Baumjohann}, W. and {Beck}, T. and {Bekkelien}, A. and {Benz}, W. and {Bonfils}, X. and {Brandeker}, A. and {Broeg}, C. and {Bruno}, G. and {B{\'a}rczy}, T. and {Cabrera}, J. and {Cameron}, A.~C. and {Charnoz}, S. and {Davies}, M.~B. and {Deleuil}, M. and {Demangeon}, O.~D.~S. and {Demory}, B. -O. and {Ehrenreich}, D. and {Erikson}, A. and {Fossati}, L. and {Fridlund}, M. and {Futyan}, D. and {Gandolfi}, D. and {Gillon}, M. and {Guedel}, M. and {Heng}, K. and {Isaak}, K.~G. and {Kiss}, L. and {Laskar}, J. and {Lecavelier des Etangs}, A. and {Lendl}, M. and {Lovis}, C. and {Magrin}, D. and {Maxted}, P.~F.~L. and {Mecina}, M. and {Mustill}, A. and {Nascimbeni}, V. and {Olofsson}, G. and {Ottensamer}, R. and {Pagano}, I. and {Pall{\'e}}, E. and {Peter}, G. and {Piotto}, G. and {Plesseria}, J. -Y. and {Pollacco}, D. and {Queloz}, D. and {Ragazzoni}, R. and {Rando}, N. and {Rauer}, H. and {Ribas}, I. and {Santos}, N.~C. and {Scandariato}, G. and {S{\'e}gransan}, D. and {Silvotti}, R. and {Simon}, A.~E. and {Smith}, A.~M.~S. and {Steller}, M. and {Szab{\'o}}, G.~M. and {Thomas}, N. and {Udry}, S. and {Viotto}, V. and {Walton}, N.~A. and {Westerdorff}, K. and {Wilson}, T.~G.},
        title = "{A transit survey to search for planets around hot subdwarfs: I. methods and performance tests on light curves from Kepler, K2, TESS, and CHEOPS}",
      journal = {arXiv e-prints},
     keywords = {Astrophysics - Earth and Planetary Astrophysics, Astrophysics - Solar and Stellar Astrophysics},
         year = 2021,
        month = apr,
          eid = {arXiv:2104.10462},
        pages = {arXiv:2104.10462},
archivePrefix = {arXiv},
       eprint = {2104.10462},
 primaryClass = {astro-ph.EP},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2021arXiv210410462V},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```



