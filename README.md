#This repository has been deprecated.
This is the directory containing source code and examples for the analytical solution of
the linearized Poisson Boltzmann solver, as described in Lotan and Head-Gordon 2006.

The src directory contains source code.  To make, open the makefile, change any
libs or includes as needed and make as follows:

		make mpe

The bin directory stores the executable, called mpe

The test directory contains a series of submit scripts and required inputs for each
option of the mpe code.  Each is described in the README in the test directory.

The doc directory contains doxygen created documentation for the source code.  It was
created by doxygen version 1.8.1.  To load as an html, open the annotated.html file in
a browser.
