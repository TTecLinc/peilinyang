---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
  
In Progress 
======

## <medium> Rare Disaster Element in HANK </medium>

_2021, Peilin Yang_

<medium>The rare disaster factor has become a powerful factor explaining the mystery of equity premium. This paper studies a heterogeneous new Keynesian model (HANK) in which rare disaster pricing factors are nested. This factor can effectively explain the excess risk premium and business cycle, and I have made a detailed comparison with the representative New Keynesian model (RANK). It proves that due to the existence of heterogeneous marginal propensity to consume (MPC), HANK has greater volatility and explains more asset premiums. In other words, inequality in the economy will lead to greater economic fluctuations. </medium>

## <medium> Bayesian Estimation of Heterogeneous Firms Distribution Dynamics </medium>

_2021, Peilin Yang_

<medium>I present a method for estimating dynamic HANK models using Bayesian estimation. The method combines the projection and perturbation solution method developed by Reiter (2009) with Bayesian estimation techniques. This combination allows the estimation procedure to incorporate in the estimation dataset time series of moments of the cross-sectional distribution of agents. I showed how the heterogeneous stochastic shock of TFP on the firms affects the micro and macro moment in the firms' distribution dynamics.</medium>


Publications and Working Papar
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


