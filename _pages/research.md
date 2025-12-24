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
      <a href="https://journals.plos.org/water/article?id=10.1371/journal.pwat.0000326" target="_blank">View Article</a>
    </div>
    
    <button class="abstract-toggle" onclick="toggleAbstract('abstract2')">View Abstract</button>
    
    <div id="abstract2" class="abstract-content">
      <h4>Abstract</h4>
      <p>Promoting regulatory compliance in the face of limited resources poses a distinct challenge to regulators, who can find within rational choice theory a diverse toolkit of policy levers – ones that change the likelihood that noncompliance is sanctioned, the size of sanctions, or the cost of compliance – but must look beyond theory to understand how such levers actually work in practice. In 1999, California introduced changes to its clean water program that modified each of these components, and in the present work we explore the impact of these changes using a mixed-methods approach. While the state's introduction of $3,000 mandatory minimum penalties for certain Clean Water Act effluent and reporting violations by permitted wastewater facilities reflected a significant step-up in enforcement, the policy also allowed small communities with financial hardship to redirect penalties toward investments in compliance. Our results suggest that the increase in sanctions was associated with decreases in violations with relatively low compliance costs (such as reporting violations), but that there may be considerable mismatch between the scale of penalties and compliance costs for keeping many types of pollutants within regulatory limits, and an underappreciation of critical factors like political pressure that are uncaptured by classical theory. We also find suggestive evidence that penalty conversions reduced pollution limit violations, and highlight tensions between their eligibility criteria and environmental justice. Our case study highlights how policy design and implementation fidelity — how closely a policy is carried out as originally intended — shape regulatory effectiveness and equity, with lessons for regulators and researchers across policy domains.</p>
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

