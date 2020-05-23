# CST_ADS_MODELS_SIMULATIONS

CST Studio and ADS Simulation files and results

This repository will be used to store some of the CST Studio and ADS simulation designs, files and their Scattering Parameters results.

1. micro_sma_impedance.cst : 
  SMA Connector pad has 1.5mm width. However the 50Ohm microstrip line for H = 6.7mil, T = 1.4mil, Er = 3.66 is 0.34mm. There   will be reflection. To prevent this a cutout is simulated. 1.5mm pad is coupled to 3rd layer ground. In this way RL =         -34dB meaning that reflected power is 0.04%

2. micro_impedance.cst : 
  micro_sma_impedance.cst simulation without sma connector RL = -22.9dB meaning that reflected power is 0.5%
  
3. wilkinson_splitter.cst : 
  Wilkinson Power Splitter for Z0 = 50Ohm transmission line where termination resistor value is 2Zo = 100Ohm and 2 ports are     Qurterwave transformers with 1.4Zo = 70Ohm resistance. The simulated attenuations at ports are -3.2dB.

4. antenna.cst : 
  Conserve case antenna model. Gain is 7.3dBi at 6GHz.
  
5. Microwave Amplifier Design Chapter 12, David Pozar, Stability Test on Keysight ADS
  
  
![sma_connector](https://user-images.githubusercontent.com/61315249/82730757-d363fa80-9d0a-11ea-9adc-0c520f208fa2.png)

![micro_impedance](https://user-images.githubusercontent.com/61315249/82730844-5be29b00-9d0b-11ea-97d6-a1ac47084fc5.png)

![wilkinson splitter](https://user-images.githubusercontent.com/61315249/82636643-bb598180-9c0b-11ea-9e72-4b63958da9f2.png)

![antenna](https://user-images.githubusercontent.com/61315249/82641666-5d319c00-9c15-11ea-9d74-befb981ba36a.png)

![stability](https://user-images.githubusercontent.com/61315249/82730664-00fc7400-9d0a-11ea-8ad4-b188a123ad76.png)
