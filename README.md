# SoliDRIL
Jupiter notebooks for Solid State Physics courses at EPFL

## TO DO LIST

The (Lower) ones are not urgent. (regular) or (R) are what we discussed

- [ ] Chapter 1: Velocity and current density(lower)

- [ ] Chapter 1: equations of motion (eqs. 1.9 - 1.10) (L)

- [ ] Hall effect(Clas-LOW)

- [x] 1.Dielectric constants sigma+epsilon: plot the functions  Drude+Insulator  (Regular)

- [ ] 2.Born- von Karman boundary conditions : particle in 1D box+ (appendixA--Reciprocal lattice(R) (k-states lattice)
      - [ ] (appendixA--illustration of reciprocal space and the Brillouin zone in 2D (draft version exists); 
      - [ ] illustrations for understanding central equation (k vs. G, etc.)
      - [ ] (appendixA--1.Real ---> Reciprocal
      - [ ] (appendixA--2Reciprocal vs k-space
      - [ ] (appendixA--3.Real/reciprocal + diffraction(x) 
      - [ ] 4.Bravis/nonbravis

- [x] 2.Density of states: 1D -- even 2d and 3d (R) illustration of density of states (would be nice also to show dependence on the dimensionality)

- [x] 2.illustration of the Fermi-Dirac distribution (slider T vs. width) (R)

- [ ] 2.Illustration of cv as function of energy integrant (Demonstrate that states close to ef contributes)

      ------

      ​

- [ ] band structure of free electrons in weak periodic potential; illustration of gaps

- [ ] ​

- [ ] tight-binding band structure of a 1D chain of identical atoms;

- [ ] tight-binding band structure of a 1D chain with alternating on-site potentials or/and transfer integrals;

- [ ] band structures of 2D lattices (triangular, square, honeycomb, kagome, Lieb);

- [ ] numerical illustration of tight-binding calculations on a model with many atoms per unit cell;

- [ ] construction of 1st, 2nd, 3rd, … Brillouin zones in 2D;

- [ ] demonstration of the definition of wavepacket in the semiclassical model;

- [ ] numerical demonstration of wavepacket propagation; 

- [ ] quantum transport in a 1D chain with impurity;

- [ ] quantum transport and quantum confinement in 2D free-electron system;

- [ ] numerical illustration of Anderson localization;

- [ ] Landau levels and quantum oscillations;

- [ ] illustration of Hund’s rule;

- [ ] phonon dispersions and vibrational modes of a 1D chain of identical atoms;

- [ ] phonon dispersions and vibrational modes of a 1D chain of atoms with alternating masses or/and alternating force constants  (draft version exists);

- [ ] animation of longitudinal and transverse vibrational modes in 2D (draft version exists);


## To check the packages installed:

```python
import pip
installed_packages = pip.get_installed_distributions()
installed_packages_list = sorted(["%s==%s" % (i.key, i.version)
     for i in installed_packages])
print(installed_packages_list)
```
