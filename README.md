# MachineLearningII
Assignments for Machine Learning II

* 1 Covid-19 Disasters
The SIR model is a 3-compartment model. Extend this model to 4 compartments, where the 4th compartment is for deaths (D). Mortality is modeled by new transitions from→D defined by the mortality rate μ. Susceptible and Recovered do not die.

(a) Derive the corresponding system of equations for S, I, R, and D. E.g., dD/dt= μI but this is not the only difference to SIR. In addition, the basic reproduction number may now depend on μ as well, how?

(b) Assume that the basic reproduction number R0 for B.1.1.7 is not exactly known but only the range R0 ∈ [3.0,4.0]. Assume that the mortality rate μ is also not exactly known but only the range μ ∈[0.4%,4%]. Study how these parameter uncertainties affect the prediction of D at t= 365d. What about the cumulative number of deaths after a year?

(c) Study numerically the effects of a hard versus soft lockdown ( by two for you reasonable values of β ), in terms of D (365d). What about the cumulative number of deaths after a year? Assume μ= 1% and a γ compatible with R0= 4.

(b,c) Can you find a way to derive and plot the effective reproduction number, R, as a function of time, given otherwise fixed parameters?

(a-d) Free choice for the initial conditions (t= 0) and initial prevalence, I (t= 0). Assume R (0) = D (0) = 0. If you choose N= 1, the compartments become fractions of the population number and you can remove N from the entire system of equations. Start with more than 1% of infected individuals (but not exactly 1%). Every plot must have a title and must display what parameters are fixed, and a legend. Every plot must be followed by a small take-home message.

* 1 Principal Component Disasters
Create labeled surrogate data sets. Perform a PCA/Class prediction with ovr logistic regression analysis as developed in the lecture.

(a) 4 blobs: Create clearly separable 4-blobs in 3d but also a ’disaster' realization with strong overlaps. Study, show and compare elbow plots and prediction boundaries.

(b) 2 touching parabola spreads as shown in the lecture, but in 3d (not 2d). Study and show elbow plot and prediction boundaries.

(a,b) Every plot must be followed by a small take-home message.
