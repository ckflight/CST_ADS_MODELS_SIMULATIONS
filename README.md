# CST_ADS_MODELS_SIMULATIONS

CST Studio and ADS Simulation files and results

This repository will be used to store some of the CST Studio and ADS simulation designs, files and their Scattering Parameters results.

1. micro_coax_impedance.cst:
  SMA Connector pad has 1.5mm width. However the 50Ohm microstrip line for H = 6.7mil, T = 1.4mil, Er = 3.66 is 0.34mm. There   will be reflection. To prevent this a cutout is simulated. 1.5mm pad is coupled to 3rd layer ground. In this way RL =         -34dB meaning that reflected power is 0.04%

2. micro_impedance.cst :
  micro_coax_impedance.cst simulation without coax RL = -22.9dB meaning that reflected power is 0.5%
  
3. wilkinson_power_splitter.cst :
  Wilkinson Power Splitter for Z0 = 50Ohm transmission line where termination resistor value is 2Zo = 100Ohm and 2 ports are     Qurterwave transformers with 1.4Zo = 70Ohm resistance. The simulated attenuations at ports are -3.2dB.



![coax](https://user-images.githubusercontent.com/61315249/82640545-776a7a80-9c13-11ea-84d4-48ef15ace78c.png)

![impedance](https://user-images.githubusercontent.com/61315249/82639283-193c9800-9c11-11ea-8a53-05aadb76ec9a.png)

![wilkinson splitter](https://user-images.githubusercontent.com/61315249/82636643-bb598180-9c0b-11ea-9e72-4b63958da9f2.png)


