---
layout: home
categories: jekyll update
permalink: /research/
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

<a href="{% link page_research.markdown %}"> [Hide Abstracts] </a>
<a href="{% link page_researchShowAbstracts.markdown %}"> **[Show Abstracts]** </a>


<br>
## Working Papers

<div class="tooltip"> <pptt> How Does a Dominant Currency Replace Another? Evidence from European Trade, </pptt> with A. Mehl & I. van Robays (European Central Bank)
</div>
[[WP Draft]](FilesToAdd/MehlMlikotaVanRobays2023_230619.pdf) [[WP CEPR]][DCSwitches-CEPR]


<div class="tooltip"> <pptt> Cross-Sectional Dynamics Under Network Structure: Theory and Macroeconomic Applications </pptt>
</div>
[[WP arXiv]][JMP-arXiv]  <a href="{% link P009_YTvideo_NBERSI.markdown %}">[Video NBER SI 2023]</a>


<br>
## Publications


<div class="tooltip"> <pptt> Sequential Monte Carlo with Model Tempering,</pptt> Mlikota, M., Schorfheide, F. (2024), <jjj>Studies in Nonlinear Dynamics & Econometrics</jjj><!--, https://doi.org/10.1515/snde-2022-0103-->
</div>
[[Link to Document]][SMC-MT] [[WP arXiv]][SMC-MT-arXiv] [[WP CEPR]][SMC-MT-CEPR] [[Code]][SMC-MT-GitHubCodes]


<div class="tooltip"> <pptt> SVARs with Occasionally-Binding Constraints,</pptt> Aruoba, S.B., Mlikota, M., Schorfheide, F., Villalvazo, S. (2022), <jjj>Journal of Econometrics</jjj><!--, 231(2), 477-499-->
</div>
[[Link to Document]][ZLB-VAR] [[WP NBER]][ZLB-VAR-NBER] [[WP CEPR]][ZLB-VAR-CEPR] [[Code]][ZLB-VAR-CodesFrank]








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


