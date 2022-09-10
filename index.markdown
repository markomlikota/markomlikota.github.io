---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!---

bundle exec jekyll serve
localhost


https://www.w3schools.com/css/css_tooltip.asp

![alt text for screen readers](picture.jpeg "Text to show on mouseover")


<p align="center">
  <img src="FilesToAdd/picture.jpeg" alt="MarineGEO circle logo" style="width:30%; border: 1px solid black; margin:0 0 0 0"/>
</p>

<img src="FilesToAdd/picture3.jpg" alt="MarineGEO circle logo" style="float: right; width:38.1966%; border: 1px solid black; margin:0 0 0 0"/>

[[mlikota@sas.upenn.edu]](mailto:mlikota@sas.upenn.edu)

<p align="center"> blabla </p>

<a href="https://www.youtube.com/embed/Tg0Ajam946o" target="_BLANK" title="Click me">[Short Video]</a>

-->




<p align="center">
  <a href="url"><img src="FilesToAdd/picture4.jpg" height="auto" width="30%" style="border-radius:50%"></a>
</p>
<h2 align="center"> Marko Mlikota</h2>


<br>

Hi!

I'm an Economics Ph.D. student
at the University of Pennsylvania.

My research interests are in time series econometrics,
with applications in (international) macro-finance. In particular, I'm analyzing how shocks propagate over time through a network of bilateral links (among industries, countries, firms, etc.).

[[CV]](FilesToAdd/CV_MM_EN.pdf) [[LinkedIn]][LinkedinProfileLink] [[GitHub]][GitHubProfileLink] [[Twitter]][TwitterProfileLink]


<br>



## Work In Progress


<div class="tooltip"> <strong>Time Series Dynamics Based On Network Structure</strong>
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Networks succinctly summarize potentially complex relations among agents or nodes by the set of bilateral links among them.
  Based on this insight, I develop a VAR where the dynamics of a (cross-sectional) time series are based on a set of bilateral links among individual series.
  I illustrate how the model’s time series properties relate to those of the network and show that it approximates the process of prices in an economy with input-output linkages and natural time lags between the production of inputs and their subsequent usage in the production of other goods.
  I apply the model to document how price shocks propagate over time through the network of input-output links across US sectors.
  Moreover, I argue that the model gives a sparse, yet flexible and intuitive way of approximating a general linear process.
  I discuss estimation strategies and the relation to other parsimony-inducing methods used for modeling high-dimensional time series, factor models in particular.
  </span>
</div>
<a href="{% link P009_YTvideo.markdown %}">[Short Video]</a>

<br>


<div class="tooltip"> <strong>Why Does a Dominant Currency Replace Another?,</strong> with A. Mehl & I. van Robays (European Central Bank)
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  This paper assesses why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses — a “trade shock” and an “exchange rate volatility shock” — stressed in recent theoretical models (Gopinath and Stein (2021) and Mukhin (2022)). We study the unique case of 13 European economies that saw marked increases in use of the euro at the expense of the US dollar for international trade invoicing. Our empirical analysis uses theory-consistent identification assumptions to identify the shocks in a panel vector autoregression, allowing for cross-country effects emphasized in theory. This setup allows us to exploit the cross-sectional dispersion in timing, speed and extent of the increase in euro-invoicing over time. Our estimates point to a preponderant role of inertia and to a stronger role of the “exchange rate volatility” shock relative to the “trade shock” in invoicing decision dynamics. Greater stability of both domestic and trading partners’ currencies vis-à-vis the euro explains about 3-13% of the increase in EUR invoicing across countries. This is consistent with predictions of models emphasizing the importance of changes to exchange rate pegs as necessary condition to break input-output linkages and complementarities in price setting that induce exporters to coordinate on the same incumbent invoicing currency.
  </span>
</div>

<br>


<div class="tooltip"> <strong>Sequential Monte Carlo with Model Tempering,</strong> with F. Schorfheide (University of Pennsylvania)
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Modern macroeconometrics often relies on time series models for which it is time- consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and a nonlinear dynamic stochastic general equilibrium model. The runtime reductions we obtain range from 27% to 88%.
  </span>
</div>
[[Working Paper CEPR]][SMC-MT-CEPR] [[Working Paper arXiv]][SMC-MT-arXiv] [[Code]][SMC-MT-GitHubCodes]


<!--
**Time Series Dynamics Based On Network Structure**
<details>
  <summary> Abstract </summary>
  Networks succinctly summarize potentially complex relations among agents or nodes by the set of bilateral links among them.
  Based on this insight, I develop a VAR where the dynamics of a (cross-sectional) time series are based on a set of bilateral links among individual series.
  I illustrate how the model’s time series properties relate to those of the network and show that it approximates the process of prices in an economy with input-output linkages and natural time lags between the production of inputs and their subsequent usage in the production of other goods.
  I apply the model to document how price shocks propagate over time through the network of input-output links across US sectors.
  Moreover, I argue that the model gives a sparse, yet flexible and intuitive way of approximating a general linear process.
  I discuss estimation strategies and the relation to other parsimony-inducing methods used for modeling high-dimensional time series, factor models in particular.

</details>

<br>


**Why Does a Dominant Currency Replace Another?,** with A. Mehl & I. van Robays (European Central Bank)
<details>
  <summary> Abstract </summary>
  This paper assesses why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses — a “trade shock” and an “exchange rate volatility shock” — stressed in recent theoretical models (Gopinath and Stein (2021) and Mukhin (2022)). We study the unique case of 13 European economies that saw marked increases in use of the euro at the expense of the US dollar for international trade invoicing. Our empirical analysis uses theory-consistent identification assumptions to identify the shocks in a panel vector autoregression, allowing for cross-country effects emphasized in theory. This setup allows us to exploit the cross-sectional dispersion in timing, speed and extent of the increase in euro-invoicing over time. Our estimates point to a preponderant role of inertia and to a stronger role of the “exchange rate volatility” shock relative to the “trade shock” in invoicing decision dynamics. Greater stability of both domestic and trading partners’ currencies vis-à-vis the euro explains about 3-13% of the increase in EUR invoicing across countries. This is consistent with predictions of models emphasizing the importance of changes to exchange rate pegs as necessary condition to break input-output linkages and complementarities in price setting that induce exporters to coordinate on the same incumbent invoicing currency.

</details>

<br>


**Sequential Monte Carlo with Model Tempering,** with F. Schorfheide (University of Pennsylvania) \
[[Working Paper CEPR]][SMC-MT-CEPR] [[Working Paper arXiv]][SMC-MT-arXiv] [[Code]][SMC-MT-GitHubCodes]
<details>
  <summary>Abstract</summary>

  Modern macroeconometrics often relies on time series models for which it is time- consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and a nonlinear dynamic stochastic general equilibrium model. The runtime reductions we obtain range from 27% to 88%.
</details>

<br>
-->


<br>
## Publications

<div class="tooltip"> <strong>SVARs with Occasionally-Binding Constraints,</strong> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S., <i> Journal of Econometrics </i>, forthcoming
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
  </span>
</div>
[[Link to Document]][ZLB-VAR] [[Working Paper NBER]][ZLB-VAR-NBER]



<!--
**SVARs with Occasionally-Binding Constraints,** Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S., _Journal of Econometrics_, forthcoming \
[[Link to Document]][ZLB-VAR] [[Working Paper NBER]][ZLB-VAR-NBER]
<details>
  <summary>Abstract</summary>

  We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.

</details>
-->



[SMC-MT-arXiv]: https://arxiv.org/abs/2202.07070
[SMC-MT-CEPR]: https://cepr.org/active/publications/discussion_papers/dp.php?dpno=17035
[SMC-MT-GitHubCodes]: https://github.com/markomlikota/SMC-MT
[ZLB-VAR]: https://www.sciencedirect.com/science/article/abs/pii/S0304407621002487?dgcid=author
[ZLB-VAR-NBER]: https://www.nber.org/papers/w28571
[LinkedinProfileLink]: https://www.linkedin.com/in/marko-mlikota-aa13b712a/
[GitHubProfileLink]: https://github.com/markomlikota
[TwitterProfileLink]: https://twitter.com/marko25mlikota




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
  width: 330px;
  background-color: #181818;
  color: #bbbbbb;
  text-align: justify;
  padding: 3px 3px;
  border-radius: 0px;
  line-height: 1.2;

  /* Position the tooltip text - see examples below! */
  position: absolute;
  z-index: 1;
  bottom: -20px;
  right: 105%;
}

/* Show the tooltip text when you mouse over the tooltip container */
.tooltip:hover .tooltiptext {
  visibility: visible;
}
</style>
