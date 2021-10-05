# Proyecto-21cm

This code provides simulations of the radio sky at 40-120 MHz. The gain pattern used is from a MIST antenna http://www.physics.mcgill.ca/mist/

Requirements: pylab, healpy, astropy, pandas

## Text files

    DS f(40,110) alpha=2,5.txt

Dynamic spectra without gain pattern for 40-110 MHz and alpha=2.5

    DS f(40,110).txt

Dynamic spectra without gain pattern for 40-110 MHz and alpha=2.54

    DS+G f(40,110) alpha=2,5.txt

Dynamic spectra with symmetric gain pattern g=g(theta) for 40-110 MHz and alpha=2.5

    DS+G f(40,110).txt

Dynamic spectra with symmetric gain pattern g=g(theta) for 40-110 MHz and alpha=2.54

    DS+G(theta,phi) alpha=2,5.txt

Dynamic spectra with complete gain pattern g=g(theta,phi) for 40-120 MHz and alpha=2.5

    DS+G(theta,phi).txt

Dynamic spectra with complete gain pattern g=g(theta,phi) for 40-120 MHz and alpha=2.54
