# Optim-Dispatch-Hydroplant

![Dashboard Screenshot](2yearsresult-picture.png)


Here, we consider a simple optimization problem related to the hourly scheduling of hydro power dispatch in a real life envionement (Luzon, Philippines). 

The goal is construct a feasible solution that maximize the revenue from electricity production, following the environmental constraints, historical market price and water balance. Here, a linear optimization (LP) algorithm takes advantage of simplicity and facility of implementation. 

At a later stage of the project, a sequence model (Machine Learning) will be develop to determine the best bid strategy for the future dispatch.

This project has been implemented using `Python 3.7.6`.

Package required:
  - import pulp as pulp
  - import matplotlib.pyplot as plt
  - import pandas as pd
  - import numpy as np
  
