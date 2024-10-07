---
layout: home
categories: jekyll update
permalink: /researchShowAbstracts/
---


<nav>
    <ul>
      <li><a href="{% link index.markdown %}">Home</a></li>
      <li><a href="/research/">Research</a></li>
      <li><a href="/teaching/">Teaching</a></li>
    </ul>
</nav>
---


# Research

<a href="{% link page_research.markdown %}"> **[Hide Abstracts]** </a>
<a href="{% link page_researchShowAbstracts.markdown %}"> [Show Abstracts] </a>


<br>
## Working Papers

<div class="tooltip"> <pptt> How Does a Dominant Currency Replace Another? Evidence from European Trade, </pptt> with A. Mehl & I. van Robays (European Central Bank)
</div>
[[WP Draft]](FilesToAdd/MehlMlikotaVanRobays2023_230619.pdf) [[WP CEPR]][DCSwitches-CEPR]
<abstr>
  We assess why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses stressed in recent theory: increased trade and reduced exchange rate volatility vis-à-vis the emergent dominant currency area. Our study focuses on 13 European economies that saw marked increases in the use of the euro at the expense of the US dollar for trade invoicing. We show how theory maps itself into a network which links together invoicing currency decisions across countries and develop a fitting Panel-Vector autoregression to jointly model invoicing, trade and exchange rate volatility dynamics across countries, while allowing for cross-country effects emphasized in theory. We identify for each country a “trade shock” and an “exchange rate volatility shock”, finding significant evidence in support of the increased trade hypothesis. Our estimates suggest that in countries where trade with the Euro Area increased, the latter explains almost 40% of the rise in euro invoicing from 1999 to 2019. In contrast, the impact of greater exchange rate stability against the euro is found to be insignificant. Importantly, a country’s invoicing decision is significantly influenced by those of other countries within the regional trade network. This effect operates mainly via bilateral trade linkages rather than strategic complementarities in export price setting, which point to the relevance of changes to input-output linkages in making or breaking dominant currencies.
</abstr>



<br>
<div class="tooltip"> <pptt> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </pptt>
</div>
[[WP arXiv]][JMP-arXiv]  <a href="{% link P009_YTvideo_NBERSI.markdown %}">[Video NBER SI 2023]</a>
<abstr>
    Many environments in economics feature a cross-section of units linked by bilateral ties. I develop a framework for studying dynamics of cross-sectional variables exploiting this network structure. It is a vector autoregression in which innovations transmit cross-sectionally only via bilateral links and which can accommodate rich patterns of how network effects of higher order accumulate over time. The model can be used to estimate dynamic network effects, with the network given or inferred from dynamic cross-correlations in the data. It also offers a dimensionality-reduction technique for modeling (cross-sectional) processes, owing to networks' ability to summarize complex relations among units by relatively few non-zero bilateral links. In a first application, I estimate how sectoral productivity shocks transmit along supply chain linkages and affect dynamics of sectoral prices in the US economy. The analysis suggests that network positions can rationalize not only the strength of a sector's impact on aggregates, but also its timing. In a second application, I model industrial production growth across 44 countries by assuming global business cycles are driven by bilateral links which I estimate. This reduces out-of-sample mean squared errors by up to 23% relative to a principal components factor model.
</abstr>


<br>

## Publications


<div class="tooltip"> <pptt> Sequential Monte Carlo with Model Tempering,</pptt> Mlikota, M., Schorfheide, F. (2024), <jjj>Studies in Nonlinear Dynamics & Econometrics</jjj><!--, https://doi.org/10.1515/snde-2022-0103-->
</div>
[[Link to Document]][SMC-MT] [[WP arXiv]][SMC-MT-arXiv] [[WP CEPR]][SMC-MT-CEPR] [[Code]][SMC-MT-GitHubCodes]
<abstr>
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
</abstr>



<br>

<div class="tooltip"> <pptt> SVARs with Occasionally-Binding Constraints,</pptt> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022), <jjj>Journal of Econometrics</jjj><!--, 231(2), 477-499-->
</div>
[[Link to Document]][ZLB-VAR] [[WP NBER]][ZLB-VAR-NBER] [[WP CEPR]][ZLB-VAR-CEPR] [[Code]][ZLB-VAR-CodesFrank]

<abstr>
    We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
</abstr>








<!-- ***************************
     *** LINKS 
     *************************** -->

[DCSwitches-CEPR]: https://cepr.org/publications/dp18264

[JMP-arXiv]: https://arxiv.org/abs/2211.13610

[SMC-MT]: https://www.degruyter.com/document/doi/10.1515/snde-2022-0103/html
[SMC-MT-arXiv]: https://arxiv.org/abs/2202.07070
[SMC-MT-CEPR]: https://cepr.org/active/publications/discussion_papers/dp.php?dpno=17035
[SMC-MT-GitHubCodes]: https://github.com/markomlikota/SMC-MT

[ZLB-VAR]: https://www.sciencedirect.com/science/article/abs/pii/S0304407621002487?dgcid=author
[ZLB-VAR-NBER]: https://www.nber.org/papers/w28571
[ZLB-VAR-CEPR]: https://cepr.org/publications/dp15923
[ZLB-VAR-CodesFrank]: https://web.sas.upenn.edu/schorf/publications/










<!-- ***************************
     *** CHANGES TO DEFAULT STYLE
     *************************** -->


<style>
/* Tooltip container */
.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 0px dotted black; /* If you want dots under the hoverable text */
}

/* Tooltip text */
.tooltip .tooltiptext {
  visibility: hidden;
  width: 250px;
  background-color: #181818;
  color: #bbbbbb;
  text-align: justify;
  padding: 1px 1px;
  border-radius: 0px;
  line-height: 1.2;
  font-size: 14px;

  /* Position the tooltip text - see examples below! */
  position: absolute;
  z-index: 1;
  bottom: -20px;
  left: -270px;
}

/* Show the tooltip text when you mouse over the tooltip container */
.tooltip:hover .tooltiptext {
  visibility: visible;
}

</style>


