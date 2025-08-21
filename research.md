---
layout: page
title: Research
---

My CV is available [here](assets/cv/samuelhigbee_cv.pdf).


## Working papers

**Experimental design for policy choice**
[(pdf)]({{ site.url }}/assets/papers/higbee_samuel_jmp.pdf)

*Job market paper*

I study how to design experiments for the objective of 
choosing optimal polices.
An experimenter wants to choose a policy to maximize welfare
subject to budget or other policy constraints.
The effects of counterfactual policies are described by a
structural econometric model governed by an unknown parameter.
The experimenter has access to some pilot data,
and has the opportunity to collect additional data through an experiment.
The joint experimental design and policy choice problem is a
dynamic optimization problem with a very high-dimensional state space,
since the chosen policy depends on the realized data.
I propose a low-dimensional approximation to the solution
and show it is asymptotically optimal under Bayes expected welfare.
The method applies to policies allocating discrete 
as well as continuous treatments,
such as cash transfers, prices, or tax credits,
and also allows targeting the policy based on covariates.
I demonstrate the method using the conditional cash transfer program
Progresa,
showing how to design an experiment to help choose a policy aimed at
increasing graduation rates and reducing gender disparities in education.
Compared to the original Progresa experiment,
the optimal experiment requires only one quarter as many observations
to obtain equally effective policies.

**Policy learning with new treatments** 
[(pdf)]({{ site.url }}/assets/papers/policy_learning_new.pdf)

*Conditionally accepted at Quantitative Economics*

I study the problem of a decision maker choosing a policy to allocate treatment to a 
heterogeneous population on the basis of experimental data that includes only a subset 
of possible treatment values.
The effects of new treatments are partially identified based on shape restrictions on 
treatment response.
I propose solving an empirical minimax regret problem to estimate the policy and show 
it has a tractable linear- and integer-programming formulation.
I prove the maximum regret of the estimator converges to the lowest possible maximum 
regret at the rate at which heterogeneous treatment effects can be estimated in the 
experimental data or N^(-1/2), whichever is slower.
I apply my results to design targeted subsidies for electrical grid connections in rural 
Kenya, and estimate that 97% of the population should be given a treatment not implemented 
in the experiment.

## Work in progress

**Distributionally robust optimal transport for program evaluation**

*with [Omkar A. Katta](https://omkarakatta.netlify.app) 
and [Guillaume Pouliot](https://sites.google.com/site/guillaumeallairepouliot/)*

Many partially identified parameters in program evaluation settings
are instances of the general Fréchet problem of bounding
a functional of a joint distribution when only its marginals are observed.
A leading example is the distribution of treatment effects.
Using data on covariates can tighten the identified set,
but doing so nonparametrically is difficult in practice.
We propose a distributionally robust optimal transport framework
for inference on the solution to the Fréchet problem
which nonparametrically incorporates covariate data
and show it delivers valid inference on these parameters.
We show our infinite-dimensional distributionally robust optimal transport
problem has a finite-dimensional linear programming formulation,
facilitating computation.

<img src="assets/images/timp_fall_crop.png" width="100%" style="padding-top:20px; padding-bottom:20px"/>

*Mount Timpanogos from Kyhv Peak. Credit: Emma Higbee*
