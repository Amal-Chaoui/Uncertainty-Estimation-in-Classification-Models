# Uncertainty-Estimation-in-Classification-Models

## Introduction 

Pancreatic Cancer has a substantial potential of malignity
and early detection of this type of disease is challenging.
Its survival rates have not changed signicantly in nearly 40 years.
The lack of standardised international guidelines in assessing suspicious
pancreatic masses is the main cause behind its high mortality
rate. 

Articial Intelligence (AI) technologies have emerged to provide
better diagnosis and treatment of diseases based on patients
clinical, personal, and medical information. However, ***Uncertainty
Quantication (UQ)*** is usually neglected when dealing with Machine
Learning predictions. 

In that regard, we present two different
approaches to uncertainty estimation. The  first one uses a recent
published work based on *Bayesian Ensembles*. The second one is
based upon the *Dempster Shafer theory of evidence*. The obtained
results are then compared in terms of uncertainty precision as well
as the way of combining evidence from different sources and suggest
that the second method gives a way of combining evidence based
on their reliability degree and provides better uncertainty handling
with respect to every patient individually. However, the major pitfall of this method lies in its computational complexity when merging pieces of evidence (in exponential time). 

This way, physicians can
better take advantage from ML models predictions for patients diagnosis
and treatment decision making.
