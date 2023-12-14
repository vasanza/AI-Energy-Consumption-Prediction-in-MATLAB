# AI-Energy-Consumption-Prediction-in-MATLAB
This MATLAB repository offers a collection of codes dedicated to predicting energy consumption using artificial intelligence techniques. These scripts and programs provide tools to develop accurate and efficient predictive models estimating energy usage. From machine learning algorithms to neural networks and advanced data processing methods, this compilation provides essential resources for researchers, students, and professionals interested in precisely predicting energy consumption using AI techniques within the MATLAB environment.

- Variables independientes (x1,....,xn): Energía, Voltaje......,etc. en t=t0 (Valor actual)
- Variable dependiente (f(x)): Energía en t=to+dt (Valor siguiente); dt=1seg
- Frecuencia de muestreo de los datos: 1 muestra por segundo (sps)
- Venta temporal de predicción: (dt=1día)

![PlotData](https://user-images.githubusercontent.com/12642226/146457419-5fc2353d-1ba6-47a3-909a-08c84e34458b.jpg)

# Dataset
- Descargar datos (.csv) desde desde repositorio (DataPort)
- Paper: https://doi.org/10.1016/j.procs.2022.07.035
- Dataset: https://ieee-dataport.org/open-access/data-server-energy-consumption-dataset
- Codigo Matlab: https://github.com/vasanza/EnergyConsumptionPrediction
- Funciones de Matlab: https://github.com/vasanza/Matlab_Code

# Related work
- https://ieeexplore.ieee.org/document/9530151
- https://ieee-dataport.org/documents/weather-monitoring-station-farms-and-agriculture

# Repository technical specifications
## To work better it is recommended:
- The main code in the project folder
- The data in a subfolder called "data"
- Put these functions in a subfolder called "src"

# Keynote
## Clone
- git status
- git clone https://github.com/vasanza/EnergyConsumptionPrediction.git
## Switched to Branch
- git branch
- git checkout NameBranch
## New Branch
- git checkout -b NameBranch
## Push
- git status
- git add .
- git status
- git commit -m "message"
- git push origin NameBrach
