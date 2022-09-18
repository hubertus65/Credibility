

# Credibility

[![The BSD License](https://img.shields.io/badge/license-BSD-brightgreen.svg?style=flat-square)](https://github.com/DLR-SR/Credibility/blob/master/LICENSE.md)

Package Credibility is a free Modelica package to add traceability, uncertainty and calibration information to scalar and 1D-table parameters in a standardized way. For details of this library, see also the journal article [Towards Modelica Models with Credibility Information](https://doi.org/10.3390/electronics11172728).

Example for the kind of information that can be added to a scalar parameter value (image is from the article above):

![SpringConstantCredibilityInfo](Credibility/Resources/Images/SpringConstantCredibility.png)

The Credibility library contains an example of a controlled drive train with scalar and 1D-table parameters with credibility information. This information is then used to demonstrate (for details see the article above):

- _optimization based calibration_ (using the commercial [DLR Optimization Modelica library](https://www.systemcontrolinnovationlab.de/the-dlr-optimization-library/)) and
- _Monte Carlo simulation_ (demonstrating in particular a new approach for utilizing table-based uncertainty in a Monte Carlo simulation).

## Main Developers

[Martin Otter](https://rmc.dlr.de/sr/en/staff/martin.otter/), Matthias Reiner, Jakub Tobolar,
[DLR - Institute of System Dynamics and Control](https://www.dlr.de/sr/en).

## Acknowledgement

The development of the Library was organized within the European ITEA3 Call6 project [UPSIM](https://www.upsim-project.eu/) – Unleash Potentials in Simulation (number 19006).The work was partially funded by the German Federal Ministry of Education and Research (BMBF, grant numbers 01IS20072H and 01IS20072G).

The development of this library is based on work carried out together with Leo Gall and Matthias Schäfer (both [LTX Simulation GmbH](https://www.ltx.de/english.html)) in the UPSIM project.
