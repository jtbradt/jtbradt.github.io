---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate in Public Policy, Harvard University

profile:
  align: right
  image: prof_pic.jpg
  address: >
    <p>124 Mt. Auburn St., Suite 175S</p>
    <p>Cambridge, MA 02138</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

My research applies insights and methods from industrial organization and public economics to the study of environmental, energy, and climate policy.  In my job market paper, I study the effect of consumer subsidies on market structure in the U.S. residential solar industry.

I graduated from Harvard College with a B.A. in Environmental Science and Public Policy and a Secondary in Economics.

I will be on the job market during AY 2023-2024.

<font size = "6">References</font>
* Professor Joseph E. Aldy \[[joseph_aldy@hks.harvard.edu](mailto:joseph_aldy@hks.harvard.edu)\]
* Professor Myrto Kalouptsidi \[[myrto@g.harvard.edu](mailto:myrto@g.harvard.edu)\]
* Professor Ariel Pakes \[[apakes@fas.harvard.edu](mailto:apakes@fas.harvard.edu)\]
* Professor Robin S. Lee \[[robinlee@fas.harvard.edu](mailto:robinlee@fas.harvard.edu)\]

<font size = "6">Selected working papers</font>
<p style="margin-bottom:0"> <strong>Job Market Paper:</strong> A Policy by Any Other Name: Unconventional Industrial Policy in the US Residential Solar Industry</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs1&quot;)">abstract</button> | <a href="/assets/pdf/papers/Bradt_JMP.pdf" target="_blank">paper</a>  ]</div>
<div class="popup" id="abs1" style="display: none;">Consumer subsidies are a common policy tool for supporting the adoption of clean, energy-efficient technologies. In addition to increasing take-up of new technologies, policymakers justify these programs as a means of stimulating infant industries, arguing that the presence of learning-by-doing and inter-firm knowledge spillovers incentivize entry. However, potential knowledge transfers reduce the incentives for firms to expand output and reduce costs by making cost reductions---in part---a public good. To evaluate this tradeoff, I estimate a dynamic structural model of the market for solar panel installations in California that endogenizes firms’ entry and exit decisions and allows for learning-by-doing with incomplete spillovers. I estimate that a 1<span>&#37;</span> increase in a firm’s experience as measured by cumulative production leads to a 0.7<span>&#37;</span> reduction in installation-specific costs and that learning spills over across firms. Counterfactual analysis reveals that existing consumer subsidy programs increased installer entry by 9<span>&#37;</span>, indicating that industry cost reductions outweigh the decrease in firms' incentives to reduce costs by expanding output. While consumer subsidies may be effective at increasing industry size, standard industrial policies such as entry subsidies likely provide greater welfare gains.</div>

<p style="margin-bottom:0">Private Benefits from Public Investment in Climate Adaptation and Resilience</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs2&quot;)">abstract</button> | <a href="/assets/pdf/papers/BradtAldy_ClimateAdaptation_230714.pdf" target="_blank">paper</a>  | <a href="/assets/pdf/slides/bradt_aldy_nber_2023.pdf" target="_blank">slides</a> ]</div>
<div class="popup" id="abs2" style="display: none;">Flood protection infrastructure investments, such as Army Corps of Engineer levees, can enhance resilience to flood risks amplified by climate change. We estimate the benefits from levees by exploiting repeat residential property transactions. In areas protected by levees, home values increase 3 percent. Levees impose adverse spillover flood risks to nearby areas that reduce affected home values by 1 percent. Capitalized benefits in protected areas are progressive, but adverse spillover impacts are regressive. While there is little variation across race in capitalized benefits at levee construction, racial sorting occurs post-construction. Capitalized residential property benefits do not exceed levee construction costs.</div>

<p style="margin-bottom:0">Spatial Sorting, Agglomeration Economies, and Travel Cost Endogeneity in Recreation Demand Models</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs3&quot;)">abstract</button> | <a href="/assets/pdf/papers/Bradt_RecDemandEndogeneity_220610.pdf" target="_blank">paper</a> ]</div>
<div class="popup" id="abs3" style="display: none;">Conventional recreation demand models assume that travel cost is exogenously determined. In reality, the costs individuals face when choosing which recreation site to visit are the result of a spatial sorting equilibrium, in which access to outdoor recreation sites and the environmental amenities to which they provide access may play a role. I explore the bias introduced by ignoring the potential for travel cost endogeneity in conventional recreation demand models and provide an instrumental variables approach to accounting for this endogeneity. I demonstrate the importance of accounting for the spatial non-uniformity of recreation sites and residences in a series of numerical simulations, finding that the instrumental variables approach ensures coverage of true parameter values. I implement the approach in a nationwide model of demand for overnight campground reservations as a function of price, water quality, and other observable site attributes. I find that not correcting for travel cost endogeneity via the instrumental variables approach nearly doubles estimates of consumers willingness-to-pay for improvements in water quality. This highlights the importance of relaxing the assumption of exogenous travel costs in real world applications.</div>

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