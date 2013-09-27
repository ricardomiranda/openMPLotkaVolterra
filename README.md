<<<<<<< HEAD
This a sample project written in Fortran to simulate a 2 layers trophic system according to Lotka-Volterra. The aim of this project is to use a Functional Programming style, not the model itself. OpenMP is used to do parallelisation.

I want to develop distributed, parallel and concurrent OO that scales and perform better than conventional OO does. In essence the plan is to use the "Functional Core, Imperative Shell" concept form Gary Bernhardt (https://www.destroyallsoftware.com).

To run it:
 - ulimit -s unlimited
 - export OMP_NUM_THREADS=4
 - f95 -xopenmp=parallel -o LVs ModulePredators.f95 ModulePrey.f95 MainLotkaVolterra.f95
 - ./LVs

This code is released under GPL so feel free to use it.

(c) Ricardo Miranda, 2013, mail@ricardomiranda.com.

=======
openMPLotkaVolterra
===================
>>>>>>> 19649599eb9c1aea04a61aa0913e3e3842322b1c
