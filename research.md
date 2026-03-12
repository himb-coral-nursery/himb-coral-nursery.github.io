---
layout: page
permalink: /research/
---

<!-- SECTION 1: STUDENT PROJECTS - Patch Reef -->
<div class="section-nursery" markdown="1">
<a id="students"></a>
<h1 class="page-title">Student Projects</h1>

<div class="full-width-section" markdown="1">

* Tyra Arends: [Population Structure of *Leptastrea purpurea* in Kane'ohe Bay](https://www.soest.hawaii.edu/oceanography/oceanwp/wp-content/uploads/2025/08/ArendsTyra_Final-Thesis-with-Edits-5.26.25.pdf) as a UH-Manoa GES Undergraduate Capstone project in 2025
* Addison Trainer: Optimizing Coral Fragmentation of Branching Corals in Hawaiʻi presented at Hawaii Conservation Conference in 2025
* Hugo Ducret: [Shading Does Not Lower Thermal Tolerance in *Montipora capitata*](https://www.researchgate.net/publication/385865085_Shading_does_not_lower_thermal_tolerance_in_the_coral_Montipora_capitata_implications_for_conservation_intervention) and [Light Availability Drives Phenotypic Plasticity in *Monitpora capitata*](https://www.biorxiv.org/content/biorxiv/early/2025/10/02/2025.09.30.679437.full.pdf) as part of a PhD thesis in 2025
* Tristan Permentier: [Proteomic Insights into the Photobiology of *Montipora capitata* in response to decreased light](https://www.researchgate.net/publication/398455891_Proteomic_insights_into_the_photobiology_of_the_Hawaiian_rice_coral_Montipora_capitata_in_response_to_decreased_light_intensity) as part of a MSc thesis in 2024
* Jasmine Awaya: [Fragment Size and Density Effects on the Growth and Survival of *Montipora capitata*](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/831cfa06-2cf7-4f53-9a57-281b7999fbb3/content) as a UH-Manoa GES Undergraduate Capstone project in 2023
* Garrett Fundakowski: Development and Impacts of Coral Built Structures (in prep) as part of a PhD thesis in 2022

</div>

<!-- SECTION 2: MONITORING - Deep Ocean -->
<div class="section-corals" markdown="1">
<a id="monitoring"></a>
<h1 class="page-title">Long-term Monitoring</h1>

<div class="full-width-section" markdown="1">

The nursery is photographed bimonthly to generate 3D models and orthomosaics of each mid-water platform. This dataset allows us to track coral health over time, measure growth rates, and identify bleaching or disease events. When combined with [environmental data](/facilities/#equipment), researchers can select corals with known histories to target traits such as thermal tolerance, high light acclimation, and other characteristics.

</div>

<!-- SLIDER IMAGE -->

<div class="image-slider-container">
  <div class="image-slider">
    <img src="/assets/images/taglab-ortho.png" alt="An Orthmosaic with Corals" class="slider-image-bottom">
    <div class="slider-overlay">
      <img src="/assets/images/taglab-outline.png" alt="An Orthmosaic with Outlined Corals" class="slider-image-top">
    </div>
    <div class="slider-button-container">
      <input type="range" min="0" max="100" value="50" class="slider-input" id="imageSlider">
      <div class="slider-button" id="sliderButton">
        <div class="slider-line"></div>
      </div>
    </div>
  </div>
  <p class="slider-caption">Slide to see a coral orthomosaic after automated segmentation.</p>
</div>

<script>
const sliderInput = document.getElementById('imageSlider');
const sliderButton = document.getElementById('sliderButton');
const overlay = document.querySelector('.slider-overlay');

sliderInput.addEventListener('input', (e) => {
  const value = e.target.value;
  overlay.style.clipPath = `inset(0 ${100 - value}% 0 0)`;
  sliderButton.style.left = `${value}%`;
});
</script>

</div>

<!-- SECTION 3: COLLABORATIONS - Sandbar -->
<div class="section-equipment" markdown="1">
<a id="collaborations"></a>
<h1 class="page-title">Collaborations</h1>

<div class="full-width-section collab-list" markdown="1">

**[Rapid Resilient Reefs for Coastal Defense (R3D)](https://arl.hawaii.edu/core-competencies/ocean-science/rapid-resilient-reefs-for-coastal-defense-r3d/)** - Applied Research Lab, Madin Lab, Coral Resilience Lab, Huang Lab (UH Manoa), Wangpraseurt Lab & Thode Lab (UCSD), Voss Lab (FAU)

---

**[UZELA: The Underwater Zooplankton Enhancement Light Array](https://www.researchgate.net/publication/388756450_Underwater_Zooplankton_Enhancement_Light_Array_UZELA_A_technology_solution_to_enhance_zooplankton_abundance_and_coral_feeding_in_bleached_and_non-bleached_corals)** - lead by [Dr. Andrea Grottoli (The Ohio State University)](https://scholar.google.com/citations?hl=en&user=uNY0GJAAAAAJ)

---

**[Mitigating Algal Competition with Fouling-Prevention Coatings for Coral Restoration and Reef Engineering](https://pubs.acs.org/doi/10.1021/acssuschemeng.4c07508)** - lead by [Dr. Daniel Wangpraseurt (UCSD Scripps)](https://scholar.google.com/citations?user=p5AxRRMAAAAJ&hl=en)

</div>
