# mcmc_larval_behaviour
R codes used in the article " Bapista et al. (2020). Does consistent individual variability in pelagic fish larval behaviour affect recruitment in nursery habitats?"

This code was used to perform linear mixed-effects models with multiple response variables (multivariate mixed models) to evaluate the relationship among activity (ACT), exploration (EXP), and exploratory activity index (EAI) at the individual level. The model was specified as follows: value ~ trait - 1 + (trait - 1 | units), where value represents the numerical variable of the five measures for each unit (individual). Trait is a categorical variable containing ACT, EXP, and EAI inserted as fixed effects, while units is a random effect with each individual inserted as a categorical variable.
Additionally, to calculate repeatability, either PI or EAI was included as the response variable, age as a fixed effect, and individuals as a random effect. Confidence intervals and intercepts for each model were obtained using 1000 bootstrap replicates.

Baptista, V., Costa, E.F.S., Carere, C. et al. Does consistent individual variability in pelagic fish larval behaviour affect recruitment in nursery habitats?. Behav Ecol Sociobiol 74, 67 (2020). https://doi.org/10.1007/s00265-020-02841-0
