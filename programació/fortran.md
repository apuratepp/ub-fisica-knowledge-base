Programació en FORTRAN
======================

Instal.lació en Mac OS X
------------------------

Mac OS X no incorpora FORTRAN de fàbrica, per això ens haurem de baixar els binaris de [High Performance Computing for Mac OS X](http://hpc.sourceforge.net/). Des de la *Terminal* executar:

### Mac OS X 10.7 (Lion)

`$ curl -LO http://prdownloads.sourceforge.net/hpc/gfortran-lion.tar.gz?download`

`$ gunzip gfortran-lion.tar.gz`

`$ sudo tar -xvf gfortran-lion.tar -C /`

### Mac OS X 10.6 (Snow Leopard)

`$ curl -LO http://prdownloads.sourceforge.net/hpc/gfortran-snwleo-intel-bin.tar.gz?download`

`$ gunzip gfortran-snwleo-intel-bin.tar.gz`

`$ sudo tar -xvf gfortran-snwleo-intel-bin.tar -C /`

### TextMate

Qualsevol editor de text serveix per escriure programes en fortran, però un molt recomanable és [TextMate](http://www.macromates.com). Per poder utilitzar el *bundle* de FORTRAN, que ens permetrà compilar i executar des del mateix editor de text, caldrà baixar-lo i instal.lar-lo:

* Baixar el *bundle* des de [textmate-fortran.tmbundle a GitHub](https://github.com/textmate/fortran.tmbundle)
* Renombrar l'arxiu *textmate-fortran.tmbundle-a933236* per *textmate-fortran.tmbundle* i copiar-lo al directori *Bundles* de la següent manera:

`$ cp -R /path-to-bundle/textmate-fortran.tmbundle TextMate/Applications/TextMate.app/Contents/SharedSupport/Bundles/`