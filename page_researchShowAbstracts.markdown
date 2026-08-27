---
layout: home
categories: jekyll update
permalink: /researchShowAbstracts/
---


<nav>
    <ul>
      <li><a href="{% link index.markdown %}"><strong>[Home]</strong></a></li>
      <li><a href="/research/">[Research]</a></li>
      <li><a href="/teaching/"><strong>[Teaching]</strong></a></li>
      <li><a href="/software/"><strong>[Software]</strong></a></li>
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


<pptt> Parameter Identification in Autoregressions under Discrete Sampling or Temporal Aggregation </pptt>
<div> Mlikota, M. (2026) </div>
[[WP arXiv]][P017-arXiv] 
<abstr>
  I consider an AR($p$) process that is observed every $q$ periods, either as a snapshot (stock variable) or as a sum over the sampling interval (flow variable).
	Under fairly mild assumptions, 
	I derive the identified set for general lag lengths $p \in \mathbb{N}$ and sampling frequencies $q \in \mathbb{N}$, 
	I bound its cardinality,
	and I provide a recipe to compute all candidate points and determine their membership in the identified set.
	My analysis supports the following conjecture:
	(i) the error term-variance is point-identified, 
	(ii) under temporal aggregation, the autoregressive parameters are point-identified, 
	and (iii) under discrete sampling they are point-identified for odd sampling frequencies and identified up to alternating sign for even sampling frequencies.
	I prove this conjecture in some settings and verify it numerically more broadly.
</abstr>

<br>


<pptt> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </pptt>
<div> Mlikota, M. (2026) </div>
[[WP arXiv]][P009-arXiv] 
<abstr>
  Many economic environments involve units linked by a network. I develop an econometric framework that derives the dynamics of cross-sectional variables from the lagged innovation transmission along fixed bilateral links and that can accommodate general patterns of how higher-order network effects accumulate over time. The proposed NVAR rationalizes the SAR model as the limit under an infinitely high frequency of lagged network interactions. The factor-representation of the NVAR suggests that at the cost of restricting factor dynamics, it naturally incorporates sparse factors as locally important nodes in the network. The NVAR can be used to estimate dynamic network effects. When the network is estimated as well, it also offers a dimensionality-reduction technique for modeling high-dimensional processes. In a first application, I show that sectoral output in an RBC economy with lagged input-output conversion follows an NVAR. In turn, I estimate that the dynamic transmission of TFP shocks along supply chains accounts for 61% of persistence in aggregate output growth, leaving minor roles for autocorrelation in exogenous TFP processes. In a second application, I forecast macroeconomic aggregates across OECD countries by estimating a network behind global business cycle dynamics. This reduces out-of-sample MSEs for one-step ahead forecasts relative to a dynamic factor model by -12% (quarterly real GDP growth) to -68% (monthly CPI inflation).
</abstr>

<br>

<pptt> Origins and Nature of Macroeconomic Instability in Vector Autoregressions </pptt>
<div> Amir-Ahmadi, P., Mlikota, M., Stevanović, D. (2025) </div>
[[WP arXiv]][P014-arXiv]
<abstr>
  For a general class of dynamic and stochastic structural models, we show that (i) non-linearity in economic dynamics is a necessary and sufficient condition for time-varying parameters (TVPs) in the reduced-form VARMA process followed by observables, and (ii) all parameters' time-variation is driven by the same, typically few sources of stochasticity: the structural shocks. Our results call into question the common interpretation that TVPs are due to "structural instabilities". Motivated by our theoretical analysis, we model a set of macroeconomic and financial variables as a TVP-VAR with a factor-structure in TVPs. This reveals that most instabilities are driven by two factors, which strongly comove, respectively, with measures of macroeconomic uncertainty and the contribution of finance to real economic activity, both of which are commonly emphasized as important sources of non-linearities in macroeconomics. Furthermore, our model yields improved forecasts relative to the standard TVP-VAR in which TVPs evolve as independent random walks.
</abstr>

<br>

<pptt> How Does a Dominant Currency Replace Another? Evidence from European Trade </pptt>
<div> Mehl, A., Mlikota, M., Ritto, J., van Robays, I. (2023) </div>
[[WP CEPR (major revision ongoing)]][P007-CEPR]
<abstr>
  Dominant currencies in international trade invoicing are extraordinarily stable, yet after the euro's launch many economies in the euro area’s neighborhood shifted markedly from US dollar to euro invoicing.
	We develop a semi-structural empirical framework to estimate how much two key forces emphasized in recent theory -- trade patterns and exchange-rate risk -- contributed to this switch in dominant-currency use. 
	In our structural model, firms choose the prices and currency denomination of their exports before exchange rates are realized, and invoicing decisions are interdependent across countries through input-output linkages and strategic interactions in destination markets. 
	To account for non-stationary dynamics, we approximate the equilibrium conditions around the previous period's equilibrium, which results in a dynamic, conditionally linear and high-dimensional state space model that links latent prices, quantities and currency shares across trade flows.
	Using observed trade, export price indices and invoicing currency shares across countries, the framework enables us to decompose the observed rise in euro invoicing into contributions from trade integration, reduced exchange-rate risk, and their propagation through the regional trade network. 
	Results based on a previous specification suggest that trade integration explains almost 40\% of the rise in euro invoicing from 1999 to 2019, whereas the impact of greater exchange rate stability against the euro is insignificant.
</abstr>


<br>



## Publications

<pptt> Sequential Monte Carlo with Model Tempering</pptt> 
<div> Mlikota, M., Schorfheide, F. (2024) </div>
<jjj>Studies in Nonlinear Dynamics & Econometrics</jjj><!--, https://doi.org/10.1515/snde-2022-0103-->
[[Link to Document]][P005-doc] [[WP arXiv]][P005-arXiv] [[WP CEPR]][P005-CEPR] [[Code]][P005-GitHub]
<abstr>
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
</abstr>

<br>

<pptt> SVARs with Occasionally-Binding Constraints</pptt>
<div> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022) </div>
<jjj>Journal of Econometrics</jjj><!--, 231(2), 477-499-->
[[Link to Document]][P006-doc] [[WP NBER]][P006-NBER] [[WP CEPR]][P006-CEPR] [[Code]][P006-CodesFrank]
<abstr>
    We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
</abstr>








<!-- ***************************
     *** LINKS 
     *************************** -->

[P007-CEPR]: https://cepr.org/publications/dp18264
[P009-arXiv]: https://arxiv.org/abs/2211.13610
[P014-arXiv]: https://arxiv.org/abs/2512.20152
[P017-arXiv]: https://arxiv.org/abs/2608.13224

[P005-doc]: https://www.degruyter.com/document/doi/10.1515/snde-2022-0103/html
[P005-arXiv]: https://arxiv.org/abs/2202.07070
[P005-CEPR]: https://cepr.org/active/publications/discussion_papers/dp.php?dpno=17035
[P005-GitHub]: https://github.com/markomlikota/SMC-MT

[P006-doc]: https://www.sciencedirect.com/science/article/abs/pii/S0304407621002487?dgcid=author
[P006-NBER]: https://www.nber.org/papers/w28571
[P006-CEPR]: https://cepr.org/publications/dp15923
[P006-CodesFrank]: https://web.sas.upenn.edu/schorf/publications/



<!-- 

<br>

<hr style="width: 33%; margin-left: 0; border: none; border-top: 1px solid #999999; opacity: 0.5;">

-->






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


