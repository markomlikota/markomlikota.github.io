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

<div> Modeling Product-Level Inflation Dynamics Along Supply Chains </div>
<div> <pptt> Mlikota, M., Zhang, X. </pptt> </div>

<div style="height: 12px;"></div>

<div> Sequential ABCs to Estimate Nonlinear DSGEs </div>
<div> <pptt> Mlikota, M., Scheidegger, S., Schorfheide, F. </pptt> </div>




<br>

## Working Papers


<div> Dynamic Innovation Transmission Through Networks: Theory, Large $T$-Inference, and the Role of Input-Output Conversion in Business Cycles </div>
<div> <pptt> Mlikota, M. (2026) </pptt> </div>
[[WP arXiv]][P009-arXiv] 
<abstr>
  I develop an econometric framework 
	that rationalizes the dynamics of a cross-sectional variable by lagged transmissions of innovations along bilateral links between units.
	The NVAR I propose is parameterized by $\alpha \in \mathbb{R}^p$, $p \in \mathbb{N}$ 
	-- showing the time profile of transmission along a direct link --
	and $q \in \mathbb{N}$ -- showing the relative frequency of network interactions to observation.
	While nesting the Spatial Autoregression and Spatial Error Model in the limit as $q \to \infty$ and producing equivalent impulse-responses in the long run for any finite $q$, 
	it can accommodate general transmission patterns over time and yields ``networked'' transition dynamics distinct from those implied by autocorrelated innovations.
	For a given network, $\alpha$ is identified at least up to alternating sign and its Gaussian Maximum Likelihood estimator is consistent and asymptotically Normal under mild assumptions.
	I then estimate an NVAR for monthly industrial production among 23 US manufacturing sectors, as derived under a Real Business Cycle economy with lagged input-output conversion (IOC), and I quantify the extent to which business cycles can be endogenized by the lagged transmission of productivity shocks along supply chains.
	Compared to an economy with contemporaneous IOC, the preferred lagged-IOC specification reduces the estimated shock-variances on average by 73% and accounts for around 85% of the persistence in aggregate output growth.
	In this environment, a single common productivity shock explains 90% of aggregate fluctuations, leaving a negligible role for sector-specific shocks once sectoral heterogeneity in the temporal exposure to common shocks is accounted for.
</abstr>

<br>

<div> Parameter Identification and Inference in Discretely Sampled or Temporally Aggregated Autoregressions </div>
<div> <pptt> Mlikota, M. (2026) </pptt> </div>
[[WP arXiv]][P017-arXiv] 
<abstr>
  I consider an AR($p$) process that is observed every $q$ periods, either as a snapshot (stock variable) or as a sum over the sampling interval (flow variable).
	I first characterize the resulting ARMA process followed by observables.
	Under fairly mild assumptions, 
	I then derive the identified set for general lag lengths $p \in \mathbb{N}$ and sampling frequencies $q \in \mathbb{N}$, 
	I bound its cardinality,
	and I provide an algorithm to compute all candidate points and determine their membership in the identified set.
	My exact but implicit characterization supports the following conjecture that I prove in some settings and verify numerically more broadly:
	(i) the error term-variance is point-identified, 
	(ii) under temporal aggregation, the autoregressive parameters are point-identified, 
	and (iii) under discrete sampling they are point-identified for odd $q$ and identified up to alternating sign for even $q$.
	My analysis supplements existing inference results that show consistency and asymptotic Normality of the Gaussian Maximum Likelihood estimator conditional on point-identification.
	Holding the number of observations fixed, I show that its precision does not necessarily decrease with $q$.
</abstr>

<br>

<div> Origins and Nature of Macroeconomic Instability in Vector Autoregressions </div>
<div> <pptt> Amir-Ahmadi, P., Mlikota, M., Stevanović, D. (2025) </pptt> </div>
[[WP arXiv]][P014-arXiv]
<abstr>
  For a general class of dynamic and stochastic structural models, we show that (i) non-linearity in economic dynamics is a necessary and sufficient condition for time-varying parameters (TVPs) in the reduced-form VARMA process followed by observables, and (ii) all parameters' time-variation is driven by the same, typically few sources of stochasticity: the structural shocks. Our results call into question the common interpretation that TVPs are due to "structural instabilities". Motivated by our theoretical analysis, we model a set of macroeconomic and financial variables as a TVP-VAR with a factor-structure in TVPs. This reveals that most instabilities are driven by two factors, which strongly comove, respectively, with measures of macroeconomic uncertainty and the contribution of finance to real economic activity, both of which are commonly emphasized as important sources of non-linearities in macroeconomics. Furthermore, our model yields improved forecasts relative to the standard TVP-VAR in which TVPs evolve as independent random walks.
</abstr>

<br>

<div> How Does a Dominant Currency Replace Another? Evidence from European Trade </div>
<div> <pptt> Mehl, A., Mlikota, M., Ritto, J., van Robays, I. (2023) </pptt> </div>
[[WP CEPR (major revision ongoing)]][P007-CEPR]
<abstr>
  Dominant currencies in international trade invoicing are extraordinarily stable, yet after the euro's launch many economies in the euro area’s neighborhood shifted markedly from US dollar to euro invoicing.
	We develop a semi-structural empirical framework to estimate how much two key forces emphasized in recent theory -- trade patterns and exchange-rate risk -- contributed to this switch in dominant-currency use. 
	In our structural model, firms choose the prices and currency denomination of their exports before exchange rates are realized, and invoicing decisions are interdependent across countries through input-output linkages and strategic interactions in destination markets. 
	To account for non-stationary dynamics, we approximate the equilibrium conditions around the previous period's equilibrium, which results in a dynamic, conditionally linear and high-dimensional state space model that links latent prices, quantities and currency shares across trade flows.
	Using observed trade, export price indices and invoicing currency shares across countries, the framework enables us to decompose the observed rise in euro invoicing into contributions from trade integration, reduced exchange-rate risk, and their propagation through the regional trade network. 
	Results based on a previous specification suggest that trade integration explains almost 40\% of the rise in euro invoicing from 1999 to 2019, whereas the impact of greater exchange rate stability against the euro is insignificant.
</abstr>




<div style="height: 16px;"></div>

## Publications

<div> Sequential Monte Carlo with Model Tempering </div>
<div> <pptt> Mlikota, M., Schorfheide, F. (2024) </pptt> </div>
<jjj>Studies in Nonlinear Dynamics & Econometrics</jjj><!--, https://doi.org/10.1515/snde-2022-0103-->
[[Link to Document]][P005-doc] [[WP arXiv]][P005-arXiv] [[WP CEPR]][P005-CEPR] [[Code]][P005-GitHub]
<abstr>
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
</abstr>

<br>

<div> SVARs with Occasionally-Binding Constraints </div>
<div> <pptt> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022) </pptt> </div>
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


