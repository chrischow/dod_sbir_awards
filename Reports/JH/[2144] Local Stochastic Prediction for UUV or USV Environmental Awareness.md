
Local Stochastic Prediction for UUV/USV Environmental Awareness
===============================================================

# Abstract


This project delivers a compact system to assess and reduce local uncertainties that impact routing and sensor operation decisions while tracking the evolution of the maritime environment around unmanned platforms at sea (UUV/USV). The system runs both at control centers and on-board the UUV/USV’s, subject to different network bandwidth and computing environments Size, Weight and Power (SWaP) constraints. The system uses the Navy ocean forecasts for initial environmental guesses and outlooks for up to 2 weeks (or more in future generations) and then implements Reduced Order Models (ROM) to update the original forecast fields, along with a local uncertainty picture (for the next 24-48 hours). The ROM solutions target the variables and parameters of relevance for the UUV/USV fleet mission planning and execution (e.g. currents and sound speed). The reduced order estimates of the parameters and variables of interest are computed from a set of dynamic modes derived from ocean ensembles (e.g. perturbed using Gaussian Mixture-Models and updated through Dynamically Orthogonal functions or constrained by reduced physics solutions). The amplitudes of the reduced modes are updated at the control centers and sent to the UUV/USV platforms using small size signals (order KB) to enable reconstruction of the new local forecasts, using a pre-loaded reduced modes set. To ensure local fitness for short time-ranges, in-situ network observations are assimilated in-stride using machine learning solutions. The forecast reconstruction code and machine learning runs are executed on both reach-back centers and on dedicated payloads and used for path optimization and environmental adaptation/adaptive sampling.  

# Award Details

|Branch|Award Year|Award Amount|Keywords|
| :---: | :---: | :---: | :---: |
|Navy|2020|$997,849|uxv environmental adaptation, stochastic environmental forecasting, autonomous vehicles path optimization, data assimilation, dynamically orthogonal solutions, reduced order ocean modeling|
  
  


[Back to Home](https://github.com/chrischow/dod_sbir_awards/Reports/JH/#2144)