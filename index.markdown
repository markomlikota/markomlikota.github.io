---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!---

cd Documents/WorkProjects/PersonalWebsite
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

% To refer to the page contained in the file "P009_...", which is in the same folder as this file: *<*a h*ref="{*% li*nk P0*09*_YTvideo*.m*arkdown %}">[Sho*rt Vide*o]</*a> (had to put asterisks to prevent this being read as a command...)


 <font size="3"> This is my text number1</font>
 <span style="color:blue">some *blue* text</span> // see colors in https://htmlcolorcodes.com

 <span style="color:#EABC7E; opacity: 0.900;"> <strong>Why Does a Dominant Currency Replace Another?,</strong></span> with A. Mehl & I. van Robays (European Central Bank)

-->




<p align="center">
  <a href="url"><img src="FilesToAdd/picture4.jpg" height="auto" width="30%" style="border-radius:50%"></a>
</p>
<h2 align="center"> Marko Mlikota</h2>


<br>

Hi!

I'm an Economics Ph.D. student
at the University of Pennsylvania.

My research interests are in time series econometrics and (international) macro-finance. In particular, I analyze the implications of networks for cross-sectional dynamics (think of prices across industries linked by the supply chain network, or economic activity across countries linked via trade and capital flows).

[[CV]](FilesToAdd/CV_MM_EN.pdf) [[Research Statement]](FilesToAdd/MM_ResearchStatement_2301.pdf)

[[Google Scholar]][GoogleScholarLink] [[GitHub]][GitHubProfileLink] [[LinkedIn]][LinkedinProfileLink] [[Twitter]][TwitterProfileLink]

Contact: mlikota@sas.upenn.edu


<br>
## Work in Progress

<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> Why Does a Dominant Currency Replace Another?,</span> with A. Mehl & I. van Robays (European Central Bank)
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  This paper assesses why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses — a “trade shock” and an “exchange rate volatility shock” — stressed in recent theoretical models (Gopinath and Stein (2021) and Mukhin (2022)). We study the unique case of 13 European economies that saw marked increases in use of the euro at the expense of the US dollar for international trade invoicing. Our empirical analysis uses theory-consistent identification assumptions to identify the shocks in a panel vector autoregression, allowing for cross-country effects emphasized in theory. This setup allows us to exploit the cross-sectional dispersion in timing, speed and extent of the increase in euro-invoicing over time. Our estimates point to a preponderant role of inertia and to a stronger role of the “exchange rate volatility” shock relative to the “trade shock” in invoicing decision dynamics. Greater stability of both domestic and trading partners’ currencies vis-à-vis the euro explains about 3-13% of the increase in EUR invoicing across countries. This is consistent with predictions of models emphasizing the importance of changes to exchange rate pegs as necessary condition to break input-output linkages and complementarities in price setting that induce exporters to coordinate on the same incumbent invoicing currency.
  </span>
</div>




<br>
## Working Papers


<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </span> [Job Market Paper]
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Many environments in economics feature a cross-section of agents or units linked by a network of bilateral ties. I develop a framework to study dynamics in these cases. It consists of a vector autoregression in which innovations transmit cross-sectionally via bilateral links and which can accommodate general patterns of how network effects of higher order accumulate over time. In a first application, I take the supply chain network of the US economy as given and document how it drives the dynamics of sectoral prices. By estimating the time profile of network effects, the model allows me to go beyond steady state comparisons and study transition dynamics induced by granular shocks. As a result of different positions in the input-output network, sectors differ in both the strength and the timing of their impact on aggregates. In a second application, I discuss how to approximate cross-sectional processes by assuming that dynamics are driven by a network and in turn estimating the latter. The proposed framework offers a sparse, yet flexible and interpretable method for doing so, owing to networks’ ability to summarize complex relations among units by relatively few non-zero bilateral links. Modeling industrial production growth across 44 countries, I obtain reductions in out-of-sample mean squared errors of up to 20% relative to a principal components factor model.
  </span>
</div>
[[WP arXiv]][JMP-arXiv]


<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> Sequential Monte Carlo with Model Tempering,</span> with F. Schorfheide (University of Pennsylvania)
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
  </span>
</div>
[[WP arXiv]][SMC-MT-arXiv] [[WP CEPR]][SMC-MT-CEPR] [[Code]][SMC-MT-GitHubCodes]





<br>
## Publications

<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> SVARs with Occasionally-Binding Constraints,</span> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022), <i> Journal of Econometrics </i>, 231(2), 477-499
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
  </span>
</div>
[[Link to Document]][ZLB-VAR] [[WP NBER]][ZLB-VAR-NBER] [[Code]][ZLB-VAR-CodesFrank]




[JMP-arXiv]: https://arxiv.org/abs/2211.13610

[SMC-MT-arXiv]: https://arxiv.org/abs/2202.07070
[SMC-MT-CEPR]: https://cepr.org/active/publications/discussion_papers/dp.php?dpno=17035
[SMC-MT-GitHubCodes]: https://github.com/markomlikota/SMC-MT

[ZLB-VAR]: https://www.sciencedirect.com/science/article/abs/pii/S0304407621002487?dgcid=author
[ZLB-VAR-NBER]: https://www.nber.org/papers/w28571
[ZLB-VAR-CodesFrank]: https://web.sas.upenn.edu/schorf/publications/

[LinkedinProfileLink]: https://www.linkedin.com/in/marko-mlikota-aa13b712a/
[GitHubProfileLink]: https://github.com/markomlikota
[TwitterProfileLink]: https://twitter.com/marko25mlikota
[GoogleScholarLink]: https://scholar.google.com/citations?hl=en&user=IFrID1kAAAAJ
[EmailLink]: mailto:mlikota@sas.upenn.edu




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
