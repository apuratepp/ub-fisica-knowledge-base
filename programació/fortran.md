Programació en FORTRAN
======================

Instal.lació en Mac OS X
------------------------

Mac OS X no incorpora FORTRAN de fàbrica, per això ens haurem de baixar els binaris de [High Performance Computing for Mac OS X](http://hpc.sourceforge.net/). Des de la *Terminal* executar:

### Mac OS X 10.7 (Lion)

`
$ curl -LO http://prdownloads.sourceforge.net/hpc/gfortran-lion.tar.gz?download
$ gunzip gfortran-lion.tar.gz
$ sudo tar -xvf gcc-bin.tar -C /
`