# SoliDRIL
Jupiter notebooks for Solid State Physics courses at EPFL

## TO DO LIST

- [x] Fermi statistics
- [ ] Periodic boundary
- [ ] Electromagnetic waves
- [ ] reciprocal space 

------

- [ ] Chapter 1: Velocity and current density

- [ ] Chapter 1: equations of motion (eqs. 1.9 - 1.10) 
- [ ] Hall effect
- [ ] Born- von Karman boundary conditions : particle in 1D box
- [ ] illustration of the Fermi-Dirac distribution (slider T vs. width)
- [ ] illustration of density of states (would be nice also to show dependence on the dimensionality)
- [ ] illustration of reciprocal space and the Brillouin zone in 2D (draft version exists); 
- [ ] band structure of free electrons in weak periodic potential; illustration of gaps
- [ ] illustrations for understanding central equation (k vs. G, etc.)
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
