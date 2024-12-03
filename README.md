# ml-hydrogen-storage
# Project Description
* This is the Masters' Thesis project titled 'Machine Learning based Designing of Hydrogen Storage' done under the guidance of Prof. Pratibha Sharma, IIT Bombay.
* The project focuses on the optimisation of hydrogen reactor design for a Light Duty Vehicle using machine learning.
# Project Features
* The reactor provided hydrogen to a PEM fuel cell stack through desorption, where it was converted to electrical energy before being fed to the vehicle engine.
* The parameters of the reactor that were used for optimising its design were: length-to-diameter ratio of the tubes, the number of tubes in the reactor, the heat transfer coefficient, and the thermal conductivity. Simulation was done in COMSOL Multiphysics with these four parameters for a period of six hours to study the variation of reaction fraction and mass flow rate.
* The four paramaters of the reactor along with time formed the input features whereas the two simulation outputs were the target variables.
* The data then underwent a detailed parametric and sensitivity analysis using design charts to study the variation of each of these parameters with reaction fraction.
* It was then fit into various machine learning models and the best performing model was chosen for prediction and identification of the optimal parameter combinations that maximise desorption.
# Conclusion
* The maximum hydrogen that could be desorbed from the metal hydride reactor was around 750 g corresponding to a gravimetric capacity of 1.6 wt%.
* The reactor was assumed to have not more than 15 tubes. The data for odd number of tubes was found using simualtions and was to predict the reaction fraction for its even counterpart.
* Random Forest Regression was taken up for predictions owing to its highest accuracy as compared to the other models. The R^2 values for odd number of tubes for different models is shown below
* Reaction fraction of 0.6496 was obtained for the worst cases of heat transfer coefficient(200 W/m^2-K) and thermal conductivity(0.1 W/m-K), L/D of 9 and 14 tubes, resulting in length of the tubes to be around 50.86 cm.
* Optimal combination for maintaining a constant mass flow rate of 8.5*10^-5kg/s(65 NLPM) had L/D of 11, 15 tubes, HTC of 600 W/m^2-K and thermal conductivity of 6 W/m-K.
