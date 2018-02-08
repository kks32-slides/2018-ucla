# Large deformation modelling in geomechanics
## MPM and LBM-DEM
> Krishna Kumar (2018), UCLA, California. 13th February 2018.

[https://kks32-slides.github.io/2018-ucla/#/](https://kks32-slides.github.io/2018-ucla/#/)

[![License](https://img.shields.io/badge/license-cc--by--4.0-brightgreen.svg)](https://creativecommons.org/licenses/by/4.0/)

Natural hazards such as landslides cause thousands of casualties and billions of dollars in infrastructure damage worldwide. According to the US Geological Survey, the number of people and infrastructures that are at risk continues to increase. Geophysical hazards usually involve a multiphase flow of dense granular solids and water. Understanding the mechanics of granular flow is of particular importance in predicting the run-out behaviour of landslides and debris flows. The dynamics of a granular flow involve three distinct scales: the microscopic scale, the mesoscale, and the macroscopic scale. Conventionally, granular flows are modelled as a continuum because they exhibit many collective phenomena at the macroscopic scale. Recent studies, however, suggest that a continuum law may be unable to capture the effect of inhomogeneities at the grain scale level, such as the orientation of force chains. Discrete element methods (DEM) are capable of simulating the micro-structural effects, however, they are computationally expensive. My research focuses on a multi-scale approach to understand the mechanics of geophysical hazards. The DEM is used to capture the micro-scale behaviour, while the macroscopic flow dynamics are modelled using a hybrid Eulerian-Lagrangian mesh-free approach called the Material Point Method (MPM). The MPM is capable of simulating large-deformation problems without suffering from the limitations of mesh distortion effects observed in the conventional Finite Element approach. 

The collapse of a granular column on a horizontal surface is a simple case of granular flow; however, a proper model that describes the flow dynamics is still lacking. The capabilities and limitations of continuum models in capturing the granular flow dynamics are explored by comparing the transient dynamics and the mechanism of energy dissipation in granular flows using both the MPM and DEM. The continuum approach is able to capture the rheology of dense granular flows (the inertial number _I_ is less than 0.1), such as the transient dynamics of slopes subjected to a lateral excitation. However, the lack of a collisional dissipation term in the continuum approach results in longer run-out distances for granular flows in dilute regimes (where the mean pressure is low). 

In contrast to aerial landslides, submarine landslides tend to flow across continental shelves reaching speeds of up to 80 mph, even on flat slopes (less than 5 degrees). The initiation and propagation of submarine flow depend mainly on the slope, density, and quantity of the material destabilised. In order to describe the mechanism of submarine granular flows, it is important to consider both the dynamics of the solid phase and the role of the ambient fluid. The DEM technique is coupled with the Lattice Boltzmann Method (LBM) to model the fluid-grain interactions in a submarine flow. The fluid phase is described using the Multiple-Relaxation-Time LBM (LBM-MRT) for numerical stability. A reduction in the radius of the grains is assumed during LBM computations to simulate the flow through the interconnected pore space in two-dimensions. 

The run-out of a granular column collapse in a fluid is compared with the evolution of a dry collapse to understand the effect of hydrodynamic forces, viscous drag and hydroplaning on the flow behaviour. The submarine granular flow dynamics is investigated by analysing the effect of hydroplaning, water entrainment, effective stresses, basal and internal frictional dissipation and viscous drag on the granular mass. The mechanism of energy dissipation, the shape of the flow front, pore-scale fluctuations, water entrainment and evolution of packing density provide evidence at a grain-scale level that describe the origin of different flow characteristics of a granular column collapse in a fluid. 

