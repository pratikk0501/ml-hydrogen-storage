# ml-hydrogen-storage
# Project Description
* This is the Masters' Thesis project titled 'Machine Learning based Designing of Hydrogen Storage' done under the guidance of Prof. Pratibha Sharma, IIT Bombay.
* The project focuses on the optimisation of hydrogen reactor design for a Light Duty Vehicle using machine learning.
# Project Features
* The reactor provided hydrogen to a PEM fuel cell stack through desorption, where it was converted to electrical energy before being fed to the vehicle engine.
* The parameters of the reactor that were used for optimising its design were: length-to-diameter ratio of the tubes, the number of tubes, the heat transfer coefficient, and the thermal conductivity. Simulation was done in COMSOL Multiphysics with these four parameters for a period of six hours to study the variation of reaction fraction and mass flow rate.
* The four paramaters of the reactor along with time formed the input features whereas the two simulation outputs were the target variables.
* The data then underwent a detailed parametric and sensitivity analysis using design charts to study the variation of each of these parameters with reaction fraction.
* It was then fit into various machine learning models and the best performing model was chosen for prediction and identification of the optimal parameter combinations that maximise desorption.
