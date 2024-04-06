# CST_ADS_MODELS_SIMULATIONS

CST Studio and ADS Simulation files and results

This repository will be used to store some of the CST Studio and ADS simulation designs, files and their Scattering Parameters results.

1. Patch_Antenna_InsetFeed_Array.cst:
   Inset fed 2 antenna array with quarterwave transformer for impedance matching


2. Directional_Coupler.cst:
   Directional coupler design with 16dB coupling with high directivity and minimum insertion loss


3. micro_sma_impedance.cst : 
  SMA Connector pad has 1.5mm width. However the 50Ohm microstrip line for H = 6.7mil, T = 1.4mil, Er = 3.66 is 0.34mm. There   will be reflection. To prevent this a cutout is simulated. 1.5mm pad is coupled to 3rd layer ground. In this way RL =         -34dB meaning that reflected power is 0.04%


4. micro_impedance.cst : 
  micro_sma_impedance.cst simulation without sma connector RL = -22.9dB meaning that reflected power is 0.5%

  
5. wilkinson_splitter.cst : 
  Wilkinson Power Splitter for Z0 = 50Ohm transmission line where termination resistor value is 2Zo = 100Ohm and 2 ports are     Qurterwave transformers with 1.4Zo = 70Ohm resistance. The simulated attenuations at ports are -3.2dB.


6. antenna.cst : 
  Conserve case antenna model. Gain is 7.3dBi at 6GHz.

  
7. Microwave Amplifier Design Chapter 12, David Pozar, Circular and K_Delta Stability Test using Keysight ADS. Scattering Parameters of Transistor E12_2.s2p and schematic are in Stability_Test1.zip

  
8. Microwave Amplifier Design Chapter 12, David Pozar, Maximum Gain(Conjugate Matching) using Keysight ADS. Scattering Parameters of Transistor E12_3.s2p and schematic are in Maximum_Gain_4GHz.zip

![photo-grid (1)](https://github.com/ckflight/CST_ADS_MODELS_SIMULATIONS/assets/61315249/5b708255-48bc-42e6-a535-c3649c9114ff)

![photo-grid](https://github.com/ckflight/CST_ADS_MODELS_SIMULATIONS/assets/61315249/6f7d1fce-2878-4eda-8e79-be9e0c434dc8)

![sma_connector](https://user-images.githubusercontent.com/61315249/82730757-d363fa80-9d0a-11ea-9adc-0c520f208fa2.png)

![micro_impedance](https://user-images.githubusercontent.com/61315249/82730844-5be29b00-9d0b-11ea-97d6-a1ac47084fc5.png)

![wilkinson](https://user-images.githubusercontent.com/61315249/82731048-d233cd00-9d0c-11ea-9aa6-ca4716847868.png)

![antenna](https://user-images.githubusercontent.com/61315249/82731095-1f17a380-9d0d-11ea-95bb-4091ee4e54d1.png)

![stability](https://user-images.githubusercontent.com/61315249/82730664-00fc7400-9d0a-11ea-8ad4-b188a123ad76.png)

![maximum_gain](https://user-images.githubusercontent.com/61315249/82808954-b27ae100-9e93-11ea-82d7-16f5bb110c3f.png)

