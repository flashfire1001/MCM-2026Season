model good: 038
nice graph: 570 984

## Task:

> develop a model to predict the location of a defective submersible based on the information transmitted from the equipments inside, which should be relevant with the currents, differing densities in the sea, and/or the geography of the sea floor. By analyzing the time at which a malfunction is reported, determine optimal initial deployment points for rescue vessels to maximize the probability of locating the submersible.
> 
> What is more, you should consider what equipment can be taken with, balancing safety and cost. You should also give a basic extrapolation of the model, so explain where it can be used in other scenes.

## key points of 038:

- predicting the trajectory
- best search strategy
  
part 1:
- Problem Background + Restatement + Literature Review + Our Work
- ![alt text](image.png)
- 3 aspect - 3 models

part 2:
Assumptions:
- this is crucial:When a submersible breaks down and loses contact with the host ship, it is always positioned on the sea floor or at some point of neutral buoyancy underwater.

Data Collection and Preparation

autoregressive integrated moving average (ARIMA) time series model [6] to predict the conditions of ocean currents. s