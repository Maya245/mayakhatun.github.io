---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<img src="/assets/images/banner.png" alt="Theoretical and Computational Chemistry Research" style="width:100%; border-radius:10px; margin-bottom:30px;">


Hi there ! I am a Postdoctoral Research Scholar in the Department of Chemistry at the North Carolina State University, USA. My research lies at the interface of theoretical chemistry, computational chemistry, and nanoscience, focusing on applying first-principles methods to understand the structure, stability, and electronic properties of atomically precise nanoclusters.

## Research Interests

- Automated Chemical Space Exploration
- Global Optimization of Nanoclusters
- Density Functional Theory (DFT)
- Excited-State Electronic Structure
- DNA-Stabilized Silver Nanoclusters
- Electronic and Optical Properties of Nanomaterials


## Selected Publications

{% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}

<ol>
{% for post in selected_publications %}
  <li>
    {% include archive-selected.html %}
  </li>
{% endfor %}
</ol>

## News & Updates

- **2026** Published in *ACS Physical Chemistry Au*
- **2024** Received the **RSC Nanoscale Horizons Best Poster Award** at the 7th International Symposium on Monolayer-Protected Clusters (ISMPC 2024), held at Pennsylvania State University, USA. 
  [Read more →](https://blogs.rsc.org/nr/2024/07/11/ismpc-2024-poster-prize-winners/)

## Contact

<div class="contact-info">

<span>
<i class="fas fa-envelope"></i>
<a href="mailto:mayakhatun429@gmail.com">Email</a>
</span>

&nbsp;&nbsp;&nbsp;

<span>
<i class="ai ai-google-scholar"></i>
<a href="https://scholar.google.com/citations?user=H9ZRanQAAAAJ&hl=en" target="_blank">
Google Scholar
</a>
</span>

&nbsp;&nbsp;&nbsp;

<span>
<i class="ai ai-researchgate"></i>
<a href="https://www.researchgate.net/profile/Maya-Khatun" target="_blank">
ResearchGate
</a>
</span>

&nbsp;&nbsp;&nbsp;

<span>
<i class="ai ai-orcid"></i>
<a href="https://orcid.org/0000-0001-9959-4061" target="_blank">
ORCID
</a>
</span>

</div>
