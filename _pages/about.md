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

Prior to starting my Ph.D., I worked at the U.S. Environmental Protection Agency and the White House Council on Environmental Quality and provided support on land conservation policy to various federal agencies for Booz Allen Hamilton. I graduated from Harvard College with a B.A. in Environmental Science and Public Policy and a Secondary in Economics.

I will be on the job market during AY 2023-2024.

<font size = "6">References</font>
* Professor Joseph E. Aldy \[[joseph_aldy@hks.harvard.edu](mailto:joseph_aldy@hks.harvard.edu)\]
* Professor Myrto Kalouptsidi \[[myrto@g.harvard.edu](mailto:myrto@g.harvard.edu)\]
* Professor Ariel Pakes \[[apakes@fas.harvard.edu](mailto:apakes@fas.harvard.edu)\]
* Professor Robin S. Lee \[[robinlee@fas.harvard.edu](mailto:robinlee@fas.harvard.edu)\]

<font size = "6">Selected working papers</font>
<p style="margin-bottom:0">A Policy by Any Other Name: Unconventional Industrial Policy in the US Residential Solar Industry <strong>(Job Market Paper)</strong></p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs1&quot;)">abstract</button> | <a href="/assets/pdf/papers/Bradt_JMP.pdf" target="_blank">paper</a>  ]</div>
<div class="popup" id="abs1" style="display: none;">Consumer subsidies are a common policy tool for supporting the adoption of clean, energy-efficient technologies. In addition to increasing take-up of new technologies, policymakers justify these programs as a means of stimulating infant industries, arguing that the presence of learning-by-doing and inter-firm knowledge spillovers incentivize entry. However, potential knowledge transfers reduce the incentives for firms to expand output and reduce costs by making cost reductions---in part---a public good. To evaluate this tradeoff, I estimate a dynamic structural model of the market for solar panel installations in California that endogenizes firms’ entry and exit decisions and allows for learning-by-doing with incomplete spillovers. I estimate that a 1\% increase in a firm’s experience as measured by cumulative production leads to a 0.7\% reduction in installation-specific costs and that learning spills over across firms. Counterfactual analysis reveals that existing consumer subsidy programs increased installer entry by 9\%, indicating that industry cost reductions outweigh the decrease in firms' incentives to reduce costs by expanding output. While consumer subsidies may be effective at increasing industry size, standard industrial policies such as entry subsidies likely provide greater welfare gains.</div>
<br>

<p style="margin-bottom:0">Private Benefits from Public Investment in Climate Adaptation and Resilience</p>
<div class="buttonbar">[ <button class="button" onclick="button(&quot;abs2&quot;)">abstract</button> | <a href="/assets/pdf/papers/BradtAldy_ClimateAdaptation_230714.pdf" target="_blank">paper</a>  | <a href="/assets/pdf/slides/bradt_aldy_nber_2023.pdf" target="_blank">slides</a> ]</div>
<div class="popup" id="abs2" style="display: none;">Flood protection infrastructure investments, such as Army Corps of Engineer levees, can enhance resilience to flood risks amplified by climate change. We estimate the benefits from levees by exploiting repeat residential property transactions. In areas protected by levees, home values increase 3 percent. Levees impose adverse spillover flood risks to nearby areas that reduce affected home values by 1 percent. Capitalized benefits in protected areas are progressive, but adverse spillover impacts are regressive. While there is little variation across race in capitalized benefits at levee construction, racial sorting occurs post-construction. Capitalized residential property benefits do not exceed levee construction costs.</div>
<br>

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