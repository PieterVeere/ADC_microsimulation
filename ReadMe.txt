The "Simulation Execution Code.R" file sets up the input parameters for the "Microsimulation.R" simulation code. A natural trajectory simulation can be set-up, as well as various treatment scenarios, or population subgroup analysis. From the "Simulation Execution Code.R", "Microsimulation.R" is loaded and at random one of the specified simulation scenario's is run. A specific scenario can be selected within the "Microsimulation.R" file, or by supplying only one possible simulation scenario.

The dataset is loaded from the "Simulation dataset folder". A population can be provided by the user, but an example patient is provided within "Simulation Execution Code.R".

The "Model Parameters" folder contains the parameters of the four statistical models used in the simluations.

Simulation output is saved in the "Simulation Output" folder in a csv format. Both cycle based and discrete event simulation results are provided.

"Dutch Mortality Rates.xlsx" contain Dutch population based age and sex specific yearly mortality probabilities. These are used for the probability of dieing in the MCI stage.

Reference for the author: Code is based on "microsimulation_2025_02_12_pv"