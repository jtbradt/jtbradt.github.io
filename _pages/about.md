---
layout: about
title: About
permalink: /
subtitle: <font color = "#828282">Assistant Professor, McCombs School of Business<br>The University of Texas at Austin</font>

profile:
  align: right
  image: UT-headshot.jpg
  address: >
    <p>CBA 5.252</p>
    <p>2110 Speedway</p>
    <p>Austin, TX 78705</p>
    <br>
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
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs6&quot;)">abstract</button> | <a href="/assets/pdf/papers/BradtAldy_ClimateAdaptation.pdf" target="_blank">paper</a> | <a href="https://www.nber.org/papers/w33633" target="_blank">nber</a>  | <a href="/assets/pdf/slides/bradt_aldy_nber_2023.pdf" target="_blank">slides</a> ]</div>
<div class="popup" id="abs6" style="display: none;">Flood protection infrastructure investments, such as Army Corps of Engineers levees, can enhance resilience to flood risks amplified by climate change. We estimate levees’ benefits by exploiting repeat residential property transactions. In areas protected by levees, home values increase 3-4 percent. Levees impose adverse spillover flood risks that reduce home values in nearby areas by 1-5 percent. Capitalized benefits in protected areas are progressive, but adverse spillover impacts are regressive. Capitalized benefits at levee construction do not vary by race, but racial sorting occurs post-construction. The local political economy of levee construction can explain the distribution of winners and losers.</div>

<p style="margin-bottom:0">Complementarities and Optimal Targeting of Technology Subsidies (w/ Frank Pinter)</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs2&quot;)">abstract</button> | <a href="/assets/pdf/papers/BradtPinter_SubsidiesAndComplementarities.pdf" target="_blank">paper</a>  | <a href="/assets/pdf/slides/bradt_pinter_iioc_2025.pdf" target="_blank">slides</a> ]</div>
<div class="popup" id="abs2" style="display: none;">Policies often implicitly ignore potential interactions between related products. This is particularly true in the case of clean, energy-efficient technologies. We develop a theory of second-best policy for interacting clean technologies where first-best Pigouvian taxation of dirty substitutes is infeasible. Optimal second-best policy involves subsidies that are a function of cross-technology substitution patterns. Ignoring these interactions is welfare-reducing due to infra-marginal take-up of the subsidies and the optimal policy accounts for this by targeting the more price-responsive clean technology. We find evidence of complementarities between solar photovoltaics and plug-in electric vehicles in California, suggesting that policymakers should consider these interactions when setting policy in this context.</div>

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