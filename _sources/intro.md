<h1 style="text-align: center;">  Example Codes for Coupled Theories in Solid Mechanics </h1>
<h3 style="text-align: center;" class="ignore-toc">  Eric M. Stewart, Shawn A. Chester, and Lallit Anand </h3>


# Welcome

This website compiles a collection of FEniCSx finite element codes for a wide array of coupled-physics theories in solid mechanics. These codes accompany the book, 
- L. Anand, E.M. Stewart, S.A. Chester. _Introduction to coupled theories in solid mechanics_. 2025, in preparation.

![](example_animation.gif)


A selection of example codes are provided for: 
1. Finite elasticity
2. Finite deformation viscoelasticity with inertial effects
3. Finite thermo-elasticity
4. Gel mechanics
5. Gel thermo-mechanics
6. Chemo-mechanically coupled Cahn-Hilliard
7. Electro-elasticity of dielectric elastomers
8. Electro-viscoelasticity of dielectric elastomers with inertial effects
9. Electro-chemo-elasticity of ionic polymers
10. Magneto-viscoelasticity of hard-magnetic soft-elastomers
11. Magneto-viscoelasticity of soft-magnetic soft-elastomers


## Running the codes

We recommend downloading or cloning the entire collection of example codes (< 30 MB of files) from the [GitHub repository](https://github.com/SolidMechanicsCoupledTheories/FEniCSx_codes), and then running example codes locally on your machine using Docker and VSCode.

A detailed guide for installing FEniCSx in a Docker container and running the notebooks using VSCode is provided both for [Mac](https://github.com/ericstewart36/finite_viscoelasticity/blob/main/FEniCSx_v08_Docker_install_mac.pdf) and [Windows](https://github.com/ericstewart36/finite_viscoelasticity/blob/main/FEniCSx_v08_Docker_install_windows.pdf). The installation process is essentially similar for the two operating systems, but the example screenshots in the instructions are from the relevant system.

These are our preferred methods for editing and running FEniCSx codes, although [many other options exist](https://fenicsproject.org/download/). 

```{important}
All codes were written for FEniCSx v0.8.0, so our instructions documents will direct you to install this specific version of FEniCSx.
```

## Citation


If you use these codes in your own research, please cite the software: 

 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14680876.svg)](https://doi.org/10.5281/zenodo.14680876)

as well as the associated textbook:

- L. Anand, E. M. Stewart, and S. A. Chester. _Introduction to coupled theories in solid mechanics_. 2025, in preparation.


BibTeX citations: 

```
@software{stewart2025,
  author       = {Stewart, E. M. and Chester, S. A. and Anand, L.},
  title        = {Example codes for coupled theories in solid mechanics},
  month        = jan,
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.14680876},
  url          = {https://doi.org/10.5281/zenodo.14680876}
}

@book{anand2025,
author={Anand, L. and Stewart, E. M. and Chester, S. A.},
         title={Introduction to coupled theories in solid mechanics},
         year={2025, in preparation.}
     }
```

## Legacy codes

"Legacy FEniCS" versions of some of the example codes presented in this repository are available in the following repository:
- [https://github.com/SolidMechanicsCoupledTheories/example_codes](https://github.com/SolidMechanicsCoupledTheories/example_codes)


