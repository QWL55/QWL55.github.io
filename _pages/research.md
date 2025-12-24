---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-item {
  margin-bottom: 3em;
  padding-bottom: 2em;
  border-bottom: 1px solid #e0e0e0;
}

.research-item:last-child {
  border-bottom: none;
}

.research-icon {
  font-size: 2em;
  margin-right: 0.5em;
  vertical-align: middle;
  color: #555;
}

.research-title {
  font-size: 1.2em;
  font-weight: bold;
  margin: 0.5em 0;
  display: inline-block;
}

.research-meta {
  margin: 0.5em 0;
  color: #666;
  font-size: 0.95em;
}

.research-links {
  margin: 0.5em 0;
}

.research-links a {
  margin-right: 1em;
  color: #0066cc;
  text-decoration: none;
}

.research-links a:hover {
  text-decoration: underline;
}

.abstract-toggle {
  background: none;
  border: none;
  color: #0066cc;
  cursor: pointer;
  padding: 0;
  margin: 0.5em 0;
  font-size: 0.95em;
  text-decoration: underline;
}

.abstract-toggle:hover {
  color: #004499;
}

.abstract-content {
  display: none;
  margin-top: 1em;
  padding: 1em;
  background-color: #f9f9f9;
  border-left: 3px solid #0066cc;
}

.abstract-content.show {
  display: block;
}

.abstract-content h4 {
  margin-top: 0;
  font-size: 1em;
  font-weight: bold;
}

.abstract-content p {
  margin: 0.5em 0;
  line-height: 1.6;
}
</style>

<div class="research-container">
  
  <div class="research-item">
    <i class="fas fa-database research-icon"></i>
    <h3 class="research-title">Enabling disaggregation of Asian American subgroups: a dataset of Wikidata names for disparity estimation</h3>
    
    <div class="research-meta">
      <p><strong>Authors:</strong> <strong>Lin Q</strong>, Ouyang D, Guage C, Gallegos IO, Goldin J, Ho DE</p>
      <p><strong>Journal:</strong> Scientific Data, 2025</p>
      <p><strong>DOI:</strong> <a href="https://doi.org/10.1038/s41597-025-04753-y" target="_blank">10.1038/s41597-025-04753-y</a></p>
    </div>
    
    <div class="research-links">
      <a href="https://www.nature.com/articles/s41597-025-04753-y" target="_blank">View Article</a>
      <a href="https://doi.org/10.1038/s41597-025-04753-y" target="_blank">More Info</a>
    </div>
    
    <button class="abstract-toggle" onclick="toggleAbstract('abstract1')">View Abstract</button>
    
    <div id="abstract1" class="abstract-content">
      <h4>Abstract</h4>
      <p>Decades of research and advocacy have underscored the imperative of surfacing – as the first step towards mitigating – racial disparities, including among subgroups historically bundled into aggregated categories. Recent U.S. federal regulations have required increasingly disaggregated race reporting, but major implementation barriers mean that, in practice, reported race data continues to remain inadequate. While imputation methods have enabled disparity assessments in many research and policy settings lacking reported race, the leading name algorithms cannot recover disaggregated categories, given the same lack of disaggregated data from administrative sources to inform algorithm design. Leveraging a Wikidata sample of over 300,000 individuals from six Asian countries, we extract frequencies of 25,876 first names and 18,703 surnames which can be used as proxies for U.S. name-race distributions among six major Asian subgroups: Asian Indian, Chinese, Filipino, Japanese, Korean, and Vietnamese. We show that these data, when combined with public geography-race distributions to predict subgroup membership, outperform existing deterministic name lists in key prediction settings, and enable critical Asian disparity assessments.</p>
    </div>
  </div>

  <div class="research-item">
    <i class="fas fa-tint research-icon"></i>
    <h3 class="research-title">Do mandatory minimum penalties and penalty relief work? Evidence from California's clean water program</h3>
    
    <div class="research-meta">
      <p><strong>Authors:</strong> Treves RJ, <strong>Lin Q</strong>, Hilderbran M, Ouyang D, Rodolfa KT, Mustain E, Ho DE</p>
      <p><strong>Journal:</strong> PLOS Water, 2025</p>
      <p><strong>DOI:</strong> <a href="https://doi.org/10.1371/journal.pwat.0000326" target="_blank">10.1371/journal.pwat.0000326</a></p>
    </div>
    
    <div class="research-links">
      <a href="https://journals.plos.org/water/article/authors?id=10.1371/journal.pwat.0000326" target="_blank">View Article</a>
      <a href="https://doi.org/10.1371/journal.pwat.0000326" target="_blank">More Info</a>
    </div>
    
    <button class="abstract-toggle" onclick="toggleAbstract('abstract2')">View Abstract</button>
    
    <div id="abstract2" class="abstract-content">
      <h4>Abstract</h4>
      <p>This study examines the impact of mandatory minimum penalties and penalty relief mechanisms on compliance within California's clean water program. Using administrative data from the California State Water Resources Control Board, we analyze how different penalty structures affect environmental violations and compliance behavior. Our findings suggest that increased sanctions are associated with decreases in certain violations, while penalty conversions may reduce pollution limit violations. The research highlights the importance of policy design and implementation fidelity in regulatory effectiveness and equity, providing evidence for policymakers on the effectiveness of different enforcement strategies in environmental regulation.</p>
    </div>
  </div>

</div>

<script>
function toggleAbstract(id) {
  const abstract = document.getElementById(id);
  const button = abstract.previousElementSibling;
  
  if (abstract.classList.contains('show')) {
    abstract.classList.remove('show');
    button.textContent = 'View Abstract';
  } else {
    abstract.classList.add('show');
    button.textContent = 'Hide Abstract';
  }
}
</script>

