***********
Methodology
***********

Internal Source Terms
=====================
In this approach, mesoscale tendencies are extracted from WRF and added as
source terms to the microscale simulation. Alternatively, the source terms may
be estimated from time-height varying profiles of velocity and temperature.
The latter approach is a topic currently under investigation.

This simulation may be run on a periodic domain, which facilitates the spin-up
of microscale-resolved turbulence.


Boundary Coupling
=================
In this approach, the mesoscale velocity and temperature solution is extracted
from the mesoscale simulation and used to specify time-varying values on
boundaries where the mass flux indices an inflow condition. Where outflow
exists, the boundary solution is extrapolated from the interior of the
computational domain. 

