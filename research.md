---
layout: page
title: Research
---

Some of my interests include:
* Experimental design
* Treatment choice and policy learning under uncertainty
* Nonparametric estimation and inference via optimal transport

## Job market paper
**Experimental design for policy choice**

*Draft coming soon*

## Working papers
**Policy learning with new treatments** [(pdf)]({{ site.url }}/assets/papers/policy_learning_new.pdf)

*Revision requested at Quantitative Economics*

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
