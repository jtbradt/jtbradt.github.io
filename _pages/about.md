---
layout: about
title: About
permalink: /
subtitle: <font color = "#828282">Assistant Professor, McCombs School of Business<br>The University of Texas at Austin</font>

profile:
  align: right
  image: UT-headshot.jpg
  address: >
      <p>CBA 5.232</p>
    <p>2110 Speedway</p>
    <p>Austin, TX 78705 </p>
    <p></p>
    <p><strong>Office hours:</strong> By appointment</p>
  

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am an Assistant Professor of Business, Government and Society and (by courtesy) of Economics at The University of Texas at Austin.  My research applies insights and methods from industrial organization and public economics to the study of environmental, energy, and climate policy. 

<strong><font size = "5">Selected working papers</font></strong>
<p style="margin-bottom:0"> A Policy by Any Other Name: Unconventional Industrial Policy in the US Residential Solar Industry</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs1&quot;)">abstract</button> | <a href="/assets/pdf/papers/Bradt_JMP.pdf" target="_blank">paper</a> ]</div>
<div class="popup" id="abs1" style="display: none;">Consumer subsidies are a common policy tool for supporting the adoption of clean energy technologies. Policymakers often justify these programs as a means of stimulating infant industries, arguing that greater demand increases industry learning-by-doing, which in turn reduces costs for potential entrants. This requires learning spillovers between firms that make experience-based cost reductions a public good. However, spillovers can reduce firms' incentives to expand output and lower costs. To evaluate this tradeoff, I estimate a dynamic structural model of the market for solar panel installations in California that endogenizes firms’ entry and exit decisions and allows for learning-by-doing with knowledge spillovers. I find that a 1<span>&#37;</span> increase in a firm’s cumulative production leads to a 0.7<span>&#37;</span> reduction in installation-specific costs and that learning spills over across firms. Counterfactual analysis reveals that a state-level consumer subsidy program increased installer entry by 9<span>&#37;</span>, indicating that industry cost reductions outweigh the decrease in firms' incentives to reduce costs by expanding output. While consumer subsidies may be effective at increasing industry size, I find that standard industrial policies such as entry subsidies provide greater welfare gains.</div>

<p style="margin-bottom:0">Private Benefits from Public Investment in Climate Adaptation and Resilience (w/ Joseph E. Aldy)</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs2&quot;)">abstract</button> | <a href="/assets/pdf/papers/BradtAldy_ClimateAdaptation_230714.pdf" target="_blank">paper</a>  | <a href="/assets/pdf/slides/bradt_aldy_nber_2023.pdf" target="_blank">slides</a> ]</div>
<div class="popup" id="abs2" style="display: none;">Flood protection infrastructure investments, such as Army Corps of Engineer levees, can enhance resilience to flood risks amplified by climate change. We estimate the benefits from levees by exploiting repeat residential property transactions. In areas protected by levees, home values increase 3 percent. Levees impose adverse spillover flood risks to nearby areas that reduce affected home values by 1 percent. Capitalized benefits in protected areas are progressive, but adverse spillover impacts are regressive. While there is little variation across race in capitalized benefits at levee construction, racial sorting occurs post-construction. Capitalized residential property benefits do not exceed levee construction costs.</div>

<p style="margin-bottom:0">Hotelling Meets Wright: Spatial Sorting and Measurement Error in Recreation Demand Models</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs3&quot;)">abstract</button> | <a href="/assets/pdf/papers/Bradt_RecDemandEndogeneity.pdf" target="_blank">paper</a> ]</div>
<div class="popup" id="abs3" style="display: none;">Conventional applications of recreation demand models likely suffer from two standard challenges with demand estimation, namely omitted variables bias and measurement error. Idiosyncratic prices in the form of individual-level travel costs can exacerbate these two challenges: the potential for non-random selection into travel costs through residential sorting and the difficulty of observing individual-level travel costs both work to bias traditional model estimates. I demonstrate the magnitude of this potential bias in conventional estimates of recreation demand models. I provide a relatively simple instrumental variables approach to address these two empirical challenges that substantially outperforms traditional estimates in numerical simulations. Replicating English et al. (2018), I find that accounting for potential selection into travel costs and measurement error through the instrumental variables approach changes estimates of the welfare costs of the 2010 Deepwater Horizon oil spill by over 20 percent.</div>

<script>
function button(id) {
  var x = document.getElementById(id);
  var ids = ["abs1", "abs2", "abs3", "abs4", "sum1", "sum2"];
  for(var i = 0; i < ids.length; i++) {
    var item = ids[i];
    if (item != id) {
      document.getElementById(item).style.display = "none";
    } else {
      if (x.style.display === "none") {
        x.style.display = "block"
      } else {
        x.style.display = "none";
      }
    }
  }	
}
</script> 