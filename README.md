# Li-V-Nb-O_structures
## Supporting Material for the Chakraborty and Karasulu et al. JMCA 2024 paper (DOI: [10.1039/D3TA08096J](https://pubs.rsc.org/en/Content/ArticleLanding/2024/TA/D3TA08096J))

'data' folder contains the tar file for the database containing ~11.5k Li-V-Nb-O crystal structures optimised with DFT (GGA/PBE+U).

Read the open-access paper [here](https://pubs.rsc.org/en/Content/ArticleLanding/2024/TA/D3TA08096J).

### Notes on methodology:

* All total energy calculations were performed using plane-wave Density Functional Theory (DFT) as implemented in the Vienna Ab Initio Simulation Package (VASP, v.6.2.1).
* The Perdew-Burke-Ernzerhof (PBE) exchange-correlation functional 27 and Projector Augmented Wave (PAW) pseudopotentials were used to represent each element.
* The Hubbard U (GGA+U) approach to the V 3d states was applied. The value of U = 3.25 eV was chosen to be consistent with those used for calculations in the Materials Project (MP) database and other studies.
* All DFT calculations were spin-polarized, initialized in a ferromagnetic spin configuration.
* A plane-wave cutoff energy of 520 eV was used to expand the orbitals, and the Brillouin zone was sampled using the Methfessel-Paxton scheme.
* Monkhorst-Pack grids with a spacing of 0.314 Å<sup>-1</sup> were used. The atomic coordinates were fully relaxed during the DFT simulations until the forces on each atom were within 0.05 eV/Å.
