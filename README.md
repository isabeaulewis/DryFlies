# DryFlies

## BIOL 432 Final Project

Members: Sam Boots, Sam Kam, Gloria Lee, Isabeau Lewis, Martina Mileva, and Darah Vlaminck

Data: https://doi.org/10.5061/dryad.rp187

Understanding how species respond to drying can help us inform how they may react to climate change. Drosophila mojavensis is a desert fly that inhabits different host cacti. Cuticular hydrocarbons (CHCs) cover the cuticles of D. mojavensis and assist in preventing dessication. The above dataset measures D. mojavensis responses to different levels of dessication exposure 

This data comes equipped with several different files - body mass data, cuticular hydrocarbon content data, mortality data, and viability data. For our analysis, we'll focus on two of the datasets: viability data and cuticular hydrocarbon data. Viability data includes information about the successful hatching of D. mojavensis eggs and cuticular hydrocarbon content measures changes in individual CHCs in response to different levels of dessication. 

We have two main questions answered. In the each of the files are specific step-by-step instructions for the code, but we'll give a brief outline here:

Question 1: Does population origin, host plant, or desiccation exposure time, yield differential stress responses in D. mojavensis?

We addressed this question in two parts. First, we conducted a PCA to see if changes in cuticular hydrocarbon content could be predicted by population, host plant, or dessication exposure time. Second, we conducted a decision tree and then randomForest to see which cuticular hydrocarbons were most important in predicting these dessication responses.

Question 2: Does sex, population, and/or cactus species, influence the viability of D. mojavensis eggs?

For this, we constructed a linear model of the above factors using the viability dataset to determine which influenced egg viability. We first checked the structure of the data. Then, we created a linear model with all possible factors. We used backwards selection to find the best fit model. Finally, we conducted an ANOVA to obtain the significance of different factors, and quality checks of our model output. Figures show the effects of each individual factor on D. mojavensis egg viability.

