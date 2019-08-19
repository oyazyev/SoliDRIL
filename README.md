# SoliDRIL
Jupiter notebooks for Solid State Physics courses at EPFL

## TO DO LIST

- [ ] Fermi statistics
- [ ] Periodic boundary
- [ ] Electromagnetic waves
- [ ] reciprocal space 

## To check the pachages installed:

```python
import pip
installed_packages = pip.get_installed_distributions()
installed_packages_list = sorted(["%s==%s" % (i.key, i.version)
     for i in installed_packages])
print(installed_packages_list)
```
