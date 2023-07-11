---
layout: page
permalink: /research/
title: Research
---
## Peer-Reviewed Journal Papers

{% assign thumbnail="right" %}

<div class="paper">
	<p><strong><a href="http://arxiv.org/abs/2111.02372" target="_blank" rel="noopener noreferrer"> Parameter Estimation Procedures for Exponential-Family Random Graph Models on Count-Valued Networks: A Comparative Simulation Study</a></strong> (<em>Social Networks</em> &nbsp; forthcoming) <a href="https://arxiv.org/pdf/2111.02372.pdf" target="_blank" rel="noopener noreferrer">[pdf]</a></p>
	{% include image.html url="../images/EstimateValuedERGMsFig5.png" caption="" height="220px" align=thumbnail %}
	<p>
	Computation remains a hurdle for analysis of valued networks using ERGMs. We implement an efficient parallelable subsampled Maximum Pseudo-Likelihood Estimation (MPLE) method, and evaluate estimation quality and speed of MPLE, Contrastive Divergence (CD), and Monte Carlo Maximum Likelihood Estimation (MCMLE). Simulation study shows that edge value variance is a key factor in method performance, while network size mainly influences their relative merits in computational time. We offer a guideline for choosing and tuning computational methods for Valued ERGM estimation.</p>
</div>

<!--
<div class="paper">
        <p><strong>Marginal-preserving Imputation of Three-way Array Data in Nested Structures, with Application to Small Areal Units</strong> (<em>Sociological Methodology</em> &nbsp; forthcoming)</p>
	{% include image.html url="../images/CrosstabImputation.png" height="210px" align=thumbnail %}
	Geospatial population data is typically organized into nested hierarchies of areal units, in which each unit is a union of units at the next lower level. Despite increasing interest in analyses at fine geographical detail, these lowest rungs of the areal unit hierarchy are often incompletely tabulated due to cost, privacy, or other considerations. We introduce a novel algorithm to impute crosstabs of up to three dimensions (e.g., race, ethnicity, and sex) from marginal data combined with data at higher levels of aggregation. Our method exactly preserves the observed fine-grained marginals, while approximating higher-order correlations observed in more complete higher-level data. We show how this approach can be used with U.S. Census data via a case study involving differences in exposure to crime across demographic groups, showing that the imputation process introduces very little error into downstream analysis, while depicting social process at the more fine-grained level.
</div>
-->

<div class="paper">
        <p><strong><a href="https://doi.org/10.1073/pnas.2121675119" target="_blank" rel="noopener noreferrer"> Geographical Patterns of Social Cohesion Drive Disparities in Early COVID Infection Hazard</a></strong> (<em>PNAS</em> 2022) <a href="https://www.pnas.org/doi/epdf/10.1073/pnas.2121675119" target="_blank" rel="noopener noreferrer">[pdf]</a></p>
	{% include image.html url="../images/combMap.jpg" caption="(A) Cohesion-related hazard in San Francisco <p>(B) Simulated infection time in San Francisco</p>" height="220px" align=thumbnail %}
	The uneven spread of COVID-19 has resulted in disparate experiences for marginalized populations in urban centers. Using computational models, we examine the effects of local cohesion on COVID-19 spread in social contact networks for the city of San Francisco, finding that more early COVID-19 infections occur in areas with strong local cohesion. This spatially correlated process tends to affect Black and Hispanic communities more than their Non-Hispanic White counterparts. Local social cohesion thus acts as a potential source of hidden risk for COVID-19 infection.
</div>

<div class="paper">
     <p><strong><a href="https://doi.org/10.1073/pnas.2011656117" target="_blank" rel="noopener noreferrer"> Spatial Heterogeneity Can Lead to Substantial Local Variations inCOVID-19 Timing and Severity</a></strong> (<em>PNAS</em> 2020) <a href="https://www.pnas.org/doi/epdf/10.1073/pnas.2011656117" target="_blank" rel="noopener noreferrer">[pdf]</a></p>
	{% include image.html url="../images/combfig1.jpeg" caption="" height="250px" align=thumbnail %}
	Standard epidemiological models for COVID-19 employ variants of compartment (SIR) models at local scales, implicitly assuming spatially uniform local mixing. Using a diffusion model based on interpersonal contact networks, this paper shows that the spread of COVID-19 has distinct timing and severity across different parts of a city. The paper demonstrates that spatial heterogeneity can produce dramatic differences in social exposures to those with the illness, and stress local healthcare systems differently in timing and extremity. <br>
</div>

## Working Papers

<div class="paper">
	<p><strong><a href="https://arxiv.org/abs/2205.02347" target="_blank" rel="noopener noreferrer"> Rooted America: Immobility and Segregation of the Inter-county Migration Networks</a></strong> <a href="https://arxiv.org/pdf/2205.02347.pdf" target="_blank" rel="noopener noreferrer">[pdf]</a></p>
	{% include image.html url="../images/RelationalApproach22.jpg" caption="Figure 1: Marginal approach versus relational approach" height="278px" align="left" %}
	{% include image.html url="../images/PoliAllFig.jpg" caption="Figure 2: Immobility from political division" height="278px" align="right" %}
	Despite the popular narrative that the United States is a "land of mobility," its internal migration rates have declined for decades, and reached a historical low. Economic and related factors were able to account for a portion of this trend, but the bulk has remained unexplained. Here, we propose a systemic, relational model of internal migration in the U.S., combining demographic, economic, political, and geographical factors with endogenous social mechanisms, with the objective of identifying factors limiting migration rates. We implement this model using valued temporal exponential-family random graph models, allowing us to calibrate it to the (valued) network of intercounty U.S. migration flows during the 2011-2015 period. Our analysis reveals a pattern of segmented immobility, where fewer people migrate between counties with dissimilar political contexts, levels of urbanization, and racial compositions. Probing our model using "knockout" experiments suggests that one would have observed approximately 3 million (17%) more intercounty migrants over the study period were the segmented immobility mechanisms inoperative. This analysis suggests that internal migration in the current era is driven not only by demographic and economic factors, but also cultural and political ones. It also reveals social and political cleavages that underlie geographical immobility in America.
</div>

