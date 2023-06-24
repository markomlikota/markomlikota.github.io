---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---




<p align="center">
  <a href="url"><img src="FilesToAdd/picture5.jpg" height="auto" style=" width:30%; border: 1px solid black; margin:0 0 0 0; border-radius:10%"></a>
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

<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> How Does a Dominant Currency Replace Another? Evidence from European Trade,</span> with A. Mehl & I. van Robays (European Central Bank)
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  We assess why a dominant currency in international trade invoicing can be replaced with another by contrasting two hypotheses stressed in recent theory: increased trade and reduced exchange rate volatility vis-à-vis the emergent dominant currency area. Our study focuses on 13 European economies that saw marked increases in the use of the euro at the expense of the US dollar for trade invoicing. We show how theory maps itself into a network which links together invoicing currency decisions across countries and develop a fitting Panel-Vector autoregression to jointly model invoicing, trade and exchange rate volatility dynamics across countries, while allowing for cross-country effects emphasized in theory. We identify for each country a “trade shock” and an “exchange rate volatility shock”, finding significant evidence in support of the increased trade hypothesis. Our estimates suggest that in countries where trade with the Euro Area increased, the latter explains almost 40% of the rise in euro invoicing from 1999 to 2019. In contrast, the impact of greater exchange rate stability against the euro is found to be insignificant. Importantly, a country’s invoicing decision is significantly influenced by those of other countries within the regional trade network. This effect operates mainly via bilateral trade linkages rather than strategic complementarities in export price setting, which point to the relevance of changes to input-output linkages in making or breaking dominant currencies.
  </span>
</div>
[[WP Draft]](FilesToAdd/MehlMlikotaVanRobays2023_230619.pdf) 



<br>
## Working Papers


<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </span>
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Many environments in economics feature a cross-section of units linked by bilateral ties. I develop a framework for studying dynamics of cross-sectional variables exploiting this network structure. It is a vector autoregression in which innovations transmit cross-sectionally only via bilateral links and which can accommodate rich patterns of how network effects of higher order accumulate over time. The model can be used to estimate dynamic network effects, with the network given or inferred from dynamic cross-correlations in the data. It also offers a dimensionality-reduction technique for modeling (cross-sectional) processes, owing to networks' ability to summarize complex relations among units by relatively few non-zero bilateral links. In a first application, I estimate how sectoral productivity shocks transmit along supply chain linkages and affect dynamics of sectoral prices in the US economy. The analysis suggests that network positions can rationalize not only the strength of a sector's impact on aggregates, but also its timing. In a second application, I model industrial production growth across 44 countries by assuming global business cycles are driven by bilateral links which I estimate. This reduces out-of-sample mean squared errors by up to 23% relative to a principal components factor model.
  </span>
</div>
[[WP arXiv]][JMP-arXiv]



<br>
## Publications


<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> Sequential Monte Carlo with Model Tempering,</span> Mlikota, M., Schorfheide, F. (2023), <i> Studies in Nonlinear Dynamics & Econometrics </i>, forthcoming
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  Modern macroeconometrics often relies on time series models for which it is time-consuming to evaluate the likelihood function. We demonstrate how Bayesian computations for such models can be drastically accelerated by reweighting and mutating posterior draws from an approximating model that allows for fast likelihood evaluations, into posterior draws from the model of interest, using a sequential Monte Carlo (SMC) algorithm. We apply the technique to the estimation of a vector autoregression with stochastic volatility and two nonlinear dynamic stochastic general equilibrium models. The runtime reductions we obtain range from 27% to 88%.
  </span>
</div>
[[Link to Document]][SMC-MT] [[WP arXiv]][SMC-MT-arXiv] [[WP CEPR]][SMC-MT-CEPR] [[Code]][SMC-MT-GitHubCodes]


<div class="tooltip"> <span style="color:#EABC7E; opacity: 0.900;"> SVARs with Occasionally-Binding Constraints,</span> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022), <i> Journal of Econometrics </i>, 231(2), 477-499
  <span class="tooltiptext">
  <strong>Abstract:</strong> <br />
  We develop a structural VAR in which an occasionally-binding constraint generates censoring of one of the dependent variables. Once the censoring mechanism is triggered, we allow some of the coefficients for the remaining variables to change. We show that a necessary condition for a unique reduced form is that regression functions for the non-censored variables are continuous at the censoring point and that parameters satisfy some mild restrictions. In our application the censored variable is a nominal interest rate constrained by an effective lower bound (ELB). According to our estimates based on U.S. data, once the ELB becomes binding, the coefficients in the inflation equation change significantly, which translates into a change of the inflation responses to (unconventional) monetary policy and demand shocks. Our results suggest that the presence of the ELB is indeed empirically relevant for the propagation of shocks. We also obtain a shadow interest rate that shows a significant accommodation in the early phase of the Great Recession, followed by a mild and steady accommodation until liftoff in 2016.
  </span>
</div>
[[Link to Document]][ZLB-VAR] [[WP NBER]][ZLB-VAR-NBER] [[Code]][ZLB-VAR-CodesFrank]





<!-- ***************************
     *** LINKS 
     *************************** -->


[JMP-arXiv]: https://arxiv.org/abs/2211.13610

[SMC-MT]: https://www.degruyter.com/document/doi/10.1515/snde-2022-0103/html
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

/** Links */
a { color: #8E645F; text-decoration: none; }
a:visited { color: #8E645F; }


</style>




<!-- ***************************
     *** HELPFUL COMMENTS 
     *************************** -->


<!---

cd Documents/WorkProjects/PersonalWebsite
bundle exec jekyll serve

Then: http://localhost:4000


https://www.w3schools.com/css/css_tooltip.asp

![alt text for screen readers](picture.jpeg "Text to show on mouseover")


<p align="center"> blabla </p>


%%%%% PICTURES:

<p align="center">
  <img src="FilesToAdd/picture.jpeg" alt="MarineGEO circle logo" style="width:30%; border: 1px solid black; margin:0 0 0 0"/>
</p>

<img src="FilesToAdd/picture3.jpg" alt="MarineGEO circle logo" style="float: right; width:38.1966%; border: 1px solid black; margin:0 0 0 0"/>

<p align="center">
  <a href="url"><img src="FilesToAdd/picture4.jpg" height="auto" width="30%" style="border-radius:50%"></a>
</p>
<h2 align="center"> Marko Mlikota</h2>


%%%%% LINKS:

[[mlikota@sas.upenn.edu]](mailto:mlikota@sas.upenn.edu)

<a href="https://www.youtube.com/embed/Tg0Ajam946o" target="_BLANK" title="Click me">[Short Video]</a>

% To refer to the page contained in the file "P009_...", which is in the same folder as this file: *<*a h*ref="{*% li*nk P0*09*_YTvideo*.m*arkdown %}">[Sho*rt Vide*o]</*a> (had to put asterisks to prevent this being read as a command...)


<font size="3"> This is my text number1</font>
<span style="color:blue">some *blue* text</span> // see colors in https://htmlcolorcodes.com

<span style="color:#EABC7E; opacity: 0.900;"> <strong>Why Does a Dominant Currency Replace Another?,</strong></span> with A. Mehl & I. van Robays (European Central Bank)



#8E645F

-->