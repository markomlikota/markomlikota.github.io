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
      <li><a href="/software/">Software</a></li>
    </ul>
</nav>
---


# Research

<a href="{% link page_research.markdown %}"> **[Hide Abstracts]** </a>
<a href="{% link page_researchShowAbstracts.markdown %}"> [Show Abstracts] </a>



<br>

## Work in Progress

<pptt> Modeling Product-Level Inflation Dynamics Along Supply Chains </pptt>
Mlikota, M., Zhang, X. 

<pptt> Sequential ABCs to Estimate Nonlinear DSGEs </pptt>
Mlikota, M., Scheidegger, S., Schorfheide, F. 


<br>



## Working Papers

<pptt> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </pptt>
<div> Mlikota, M. (2026) </div>
[[WP arXiv]][JMP-arXiv] 
<abstr>
  Many economic environments involve units linked by a network. I develop an econometric framework that derives the dynamics of cross-sectional variables from the lagged innovation transmission along fixed bilateral links and that can accommodate general patterns of how higher-order network effects accumulate over time. The proposed NVAR rationalizes the SAR model as the limit under an infinitely high frequency of lagged network interactions. The factor-representation of the NVAR suggests that at the cost of restricting factor dynamics, it naturally incorporates sparse factors as locally important nodes in the network. The NVAR can be used to estimate dynamic network effects. When the network is estimated as well, it also offers a dimensionality-reduction technique for modeling high-dimensional processes. In a first application, I show that sectoral output in an RBC economy with lagged input-output conversion follows an NVAR. In turn, I estimate that the dynamic transmission of TFP shocks along supply chains accounts for 61% of persistence in aggregate output growth, leaving minor roles for autocorrelation in exogenous TFP processes. In a second application, I forecast macroeconomic aggregates across OECD countries by estimating a network behind global business cycle dynamics. This reduces out-of-sample MSEs for one-step ahead forecasts relative to a dynamic factor model by -12% (quarterly real GDP growth) to -68% (monthly CPI inflation).
</abstr>

<br>

<pptt> Origins and Nature of Parameter Instability in Vector Autoregressions </pptt>
<div> Amir-Ahmadi, P., Mlikota, M., Stevanović, D. (2025) </div>
[[WP arXiv]][AAMS-arXiv]
<abstr>
  For a general class of dynamic and stochastic structural models, we show that (i) non-linearity in economic dynamics is a necessary and suﬃcient condition for time-varying parameters (TVPs) in the reduced-form VARMA process followed by observables, and (ii) all parameters’ time-variation is driven by the same, typically few sources of stochasticity: the structural shocks. Our results call into question the common interpretation that TVPs are due to “structural instabilities”. Motivated by our theoretical analysis, we model a set of macroeconomic and financial variables as a TVP-VAR with a factor-structure in TVPs. This reveals that most instabilities are driven by a few factors, which comove strongly with measures of macroeconomic uncertainty and the contribution of finance to real economic activity, commonly emphasized as important sources of non-linearities in macroeconomics. Furthermore, our model yields improved forecasts relative to the standard TVP-VAR where TVPs evolve as independent random walks.
</abstr>

<br>

<pptt> How Does a Dominant Currency Replace Another? Evidence from European Trade </pptt>
<div> Mehl, A., Mlikota, M., van Robays, I. (2023) </div>
[[WP Draft]](FilesToAdd/MehlMlikotaVanRobays2023_230619.pdf) [[WP CEPR]][DCSwitches-CEPR]
<abstr>
  We assess why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses stressed in recent theory: increased trade and reduced exchange rate volatility vis-à-vis the emergent dominant currency area. Our study focuses on 13 European economies that saw marked increases in the use of the euro at the expense of the US dollar for trade invoicing. We show how theory maps itself into a network which links together invoicing currency decisions across countries and develop a fitting Panel-Vector autoregression to jointly model invoicing, trade and exchange rate volatility dynamics across countries, while allowing for cross-country effects emphasized in theory. We identify for each country a “trade shock” and an “exchange rate volatility shock”, finding significant evidence in support of the increased trade hypothesis. Our estimates suggest that in countries where trade with the Euro Area increased, the latter explains almost 40% of the rise in euro invoicing from 1999 to 2019. In contrast, the impact of greater exchange rate stability against the euro is found to be insignificant. Importantly, a country’s invoicing decision is significantly influenced by those of other countries within the regional trade network. This effect operates mainly via bilateral trade linkages rather than strategic complementarities in export price setting, which point to the relevance of changes to input-output linkages in making or breaking dominant currencies.
</abstr>


<br>



## Publications

<pptt> Sequential Monte Carlo with Model Tempering</pptt> 
<div> Mlikota, M., Schorfheide, F. (2024) </div>
<jjj>Studies in Nonlinear Dynamics & Econometrics</jjj><!--, https://doi.org/10.1515/snde-2022-0103-->
[[Link to Document]][SMC-MT] [[WP arXiv]][SMC-MT-arXiv] [[WP CEPR]][SMC-MT-CEPR] [[Code]][SMC-MT-GitHubCodes]
<abstr>
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
</abstr>

<br>

<pptt> SVARs with Occasionally-Binding Constraints</pptt>
<div> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022) </div>
<jjj>Journal of Econometrics</jjj><!--, 231(2), 477-499-->
[[Link to Document]][ZLB-VAR] [[WP NBER]][ZLB-VAR-NBER] [[WP CEPR]][ZLB-VAR-CEPR] [[Code]][ZLB-VAR-CodesFrank]
<abstr>
    We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
</abstr>








<!-- ***************************
     *** LINKS 
     *************************** -->

[DCSwitches-CEPR]: https://cepr.org/publications/dp18264

[JMP-arXiv]: https://arxiv.org/abs/2211.13610
[AAMS-arXiv]: https://arxiv.org/abs/2512.20152

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


