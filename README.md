The relationship between State of Charge (SoC) and Open-Circuit Voltage (OCV) is fundamental for evaluating battery performance, efficiency, and health. This relationship is influenced by various factors, including temperature and the specific chemistry of the battery. Understanding this interplay is crucial for battery management systems (BMS) and optimizing battery usage in  electric vehicles 

The relationship between SoC and OCV is generally nonlinear. This nonlinearity arises from the electrochemical processes occurring within the battery, which vary with the state of charge. While studies suggest that this relationship can be modeled using high-order polynomial equations,  I have considered a third-order polynomial can provide a simplified approximation for understanding the generalized relationship


OCV = (a0 + a1 * SOC + a2 * SOC**2) + (b0 + b1 * (temperature - 25))


Provided the the coeffiecients a0,a1,a2,b0,b1, temperature of the the cell the dashboard will provide the OCV at the particular moment.

The a0,a1,a2,b0,b1 coefficients can be determined using cell testing  , Temperature of the Cell is provided by the user as a input 

The Dashboard will also provide the entire SOC vs OCV curve 
