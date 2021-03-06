BuildingsPy
-----------

.. image:: https://travis-ci.org/lbl-srg/BuildingsPy.svg?branch=master
    :target: https://travis-ci.org/lbl-srg/BuildingsPy

BuildingsPy is a Python package that can be used to

* run Modelica simulation using Dymola or JModelica
* process ``*.mat`` output files that were generated by Dymola, JModelica or OpenModelica.
* run unit tests as part of the library development.

The package provides functions to extract data series from
the output file for further use in the python packages
matplotlib for plotting and SciPy for scientific computing.

Documentation is available at http://simulationresearch.lbl.gov/modelica/buildingspy/

The license is at buildingspy/license.txt

Cloning Instructions
~~~~~~~~~~~~~~~~~~~~

Version ``2.0.0`` includes the comparison tool ``funnel`` as a ``git`` submodule.

* To clone the repository for the first time run: ``git clone --recurse-submodules https://github.com/lbl-srg/BuildingsPy.git``
* If you have already cloned the repository, checkout the master branch and run: ``git submodule update --init --recursive``
