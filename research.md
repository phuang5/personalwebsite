---
layout: page
permalink: /research/
title: Research

---

## Peer-Reviewed Journal

{% assign thumbnail="left" %}


<p><strong><a href="https://doi.org/10.1073/pnas.2011656117"> Spatial Heterogeneity Can Lead to Substantial Local Variations inCOVID-19 Timing and Severity</a></strong> (<em>PNAS</em> 2020)</p>

{% include image.html url="../images/combfig1.jpeg" caption="" height="250px" align=thumbnail %}
Standard epidemiological models for COVID-19 employ variants of compartment (SIR) models at local scales, implicitly assuming spatially uniform local mixing. Using a diffusion model based on interpersonal contact networks, this paper shows that the spread of COVID-19 has distinct timing and severity across different parts of a city. The paper demonstrates that spatial heterogeneity can produce dramatic differences in social exposures to those with the illness, and stress local healthcare systems differently in timing and extremity. <br>

---

## Working Paper

<p><strong>Parameter Estimation Procedures for Exponential-Family Random Graph Models on Count-Valued Networks: A Comparative Simulation Study</strong></p>

{% include image.html url="../images/EstimateValuedERGMsFig3.jpeg" caption="" height="250px" align=thumbnail %}
The exponential-family random graph models (ERGMs) have emerged as an important framework for modeling social and other networks.  ERGMs for valued networks are less well-studied than their unvalued counterparts, and pose particular computational challenges. Networks with edge values on the non-negative integers (count-valued networks) are an important such case, with applications ranging from migration and trade flow data to data on frequency of interactions and encounters. Here, we propose an efficient maximum pseudo-likelihood estimation (MPLE) scheme for count-valued ERGMs, and compare its performance with existing Contrastive Divergence (CD) and Monte Carlo Maximum Likelihood Estimation (MCMLE) approaches via a simulation study based on migration flow networks in two U.S states.  Our results suggest that edge value variance is a key factor in method performance, with high-variance edges posing a particular challenge for CD.  MCMLE can work well but requires careful seeding in the high-variance case, and the MPLE itself performs well when edge variance is high.
