---
title: ""
permalink: /research/
author_profile: true
---

### Working Papers

"Paying at the pump and the ballot box: Electoral penalties of motor fuel taxes" with 
[Gian-Claudia Sciara][gcs] and [Andrew Waxman][arw]. 
<span class="inline-controls">
  <a href="https://papers.ssrn.com/abstract=4999378"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
  <button onclick="toggleAbstract('abstract1', event)" class="abstract-button">[Abstract]</button>
</span>

<div id="abstract1" class="abstract">
  <p>
    Perhaps the greatest challenge to addressing climate change comprehensively through government policy in the U.S. has been limited political feasibility. We investigate whether politicians are punished by voters for increasing motor fuel taxes by compiling a comprehensive dataset on state legislative election outcomes and gasoline taxes. Leveraging a difference-in-discontinuities research design, we estimate the effect of legislated gasoline tax changes on incumbent state legislators' subsequent electoral outcomes. For very close elections, we show how the incumbency advantage attenuates when gasoline tax increases have been legislated in the intervening legislative session. Specifically, we find a small, but economically and statistically meaningful decrease in the incumbency advantage of 1.3 to 1.9 percentage points for Republican and Democratic incumbents, respectively. This penalty represents 14-21% of the overall electoral advantage of incumbents in our sample, which highlights the relative importance of environmental and energy taxes in voter priorities.
  </p>
</div>

### Work in Progress

"Optimal congestion pricing in road networks" with [Avralt-Od Purevjav][aop] and [Shanjun Li][sl].

"Bridges in Bangladesh" with [Alejandro Molnar][am] and [Forhad Shilpi][fs].

<!--<h2 id="active">
Active Research
</h2>-->

<!--<h2 id="pubs">
Publications
</h2>-->

### Publications

"[Public transport and urban structure](https://doi.org/10.1016/j.ecotra.2021.100232)" with [Leonardo J. Basso][ljb], and [Hugo E. Silva][hes]. *Economics of Transportation* 28 (2021): 100232. <a href="/files/research/transit-urban-structure.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>

<!-- ### Pre-Doctoral Work

"[Impact of a loan-based public transport fare system on fare evasion: Experience of Transantiago, Santiago, Chile](https://doi.org/10.3141%2F2544-03)" with Alejandro Schmidt, Christopher Bucknell, [Juan Carlos Muñoz][jcm], and Carolina Simonetti. *Transportation Research Record* 2544, no. 1 (2016): 20-27.

"[Increasing the speed: Case study from Santiago, Chile](https://doi.org/10.3141%2F2539-08)" with Alejandro Schmidt, Christopher Bucknell, [Juan Carlos Muñoz][jcm], and Carolina Simonetti. *Transportation Research Record* 2539, no. 1 (2016): 65-71.

"[Using travel time data to generate aggregated measures of traffic](https://doi.org/10.3141%2F2422-11)" with [Juan C. Herrera][jch]. *Transportation Research Record* 2422, no. 1 (2014): 96-103. -->

[am]: https://alejandromolnar.github.io
[aop]: https://www.avraltodpurevjav.com
[fs]: https://sites.google.com/site/decrgforhadshilpi/
[gcs]: https://soa.utexas.edu/faculty/gian-claudia-sciara
[ljb]: http://www.leonardojbasso.cl/index.html
[hes]: https://sites.google.com/site/hugosilvam/
[sl]: http://li.dyson.cornell.edu
[jch]: https://www.ing.uc.cl/academicos-e-investigadores/juan-carlos-herrera-maldonado/
[jcm]: https://www.ing.uc.cl/en/academicos-e-investigadores/juan-carlos-munoz-abogabir/
[arw]: https://www.andrewrwaxman.com

<style>
  .inline-controls {
    white-space: nowrap;
  }
  .abstract-button {
    border: none;
    background: none;
    font-size: 0.9em;
    color: #08306b;
    cursor: pointer;
    padding: 0;
  }
  .abstract {
    display: none;
    font-size: 0.8em;
    margin: 0.5em 0 1em 1em;
    border-left: 2px solid #eee;
    padding-left: 0.8em;
    text-align: justify;
  }
</style>

<script>
  function toggleAbstract(id, event) {
    const abstract = document.getElementById(id);
    const btn = event.target;
    if (abstract.style.display === "none") {
      abstract.style.display = "block";
      btn.textContent = "[Hide abstract]";
    } else {
      abstract.style.display = "none";
      btn.textContent = "[Abstract]";
    }
  }
</script>
