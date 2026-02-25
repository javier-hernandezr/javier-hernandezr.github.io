---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

{% include base_path %}

Below are selected highlights from my conference presentations. 
For a complete list of talks, posters, and workshops, please see
my [full CV](/files/CV-Javier_Hernandez.pdf).

---

## 2025

- **Unraveling the effect of spin-orbit coupling in DpgC-catalyzed peroxidation** *(oral)*
  VII Jornadas de Jóvenes Investigadores, Universidad de Salamanca, Spain.

- **Non-Adiabatic Dynamics of Excited States in Tetraphenylpyrazine: From Monomer to Dimer** *(invited talk)*
  Third General Meeting COSY Cost Action, Bologna, Italy.

- **Photoinduced Nonadiabatic Processes in Tetraphenyl-Substituted Azaheterocycles** *(oral)*
  15th Symposium on Computing π-conjugated compounds, Università di Siena, Italy.

## 2024

- **Quantum dynamics of the spin-forbidden peroxidation catalyzed by DpgC** *(oral)*
  13th IMAMPC, University of Warsaw, Poland.

- **N-doped PAH non-adiabatic dynamics with the ML-MCTDH method** *(invited talk)*
  Second General Meeting COSY Cost Action, Wroclaw, Poland.

- **Cyclopropanone as a benchmark system for non-adiabatic dynamics** *(flash talk)*
  CECAM Workshop "Standardizing nonadiabatic dynamics", Paris, France.

- **A step towards quantum dynamics in tetraphenylpyrazine molecular crystals** *(oral)*
  15th Young Researchers in Atomic and Molecular Physics Conf., RSEQ, Valencia, Spain.

## 2023

- **Quantum effects of the enzymatic peroxidation of organic substrates** *(flash talk)*
  XXXIX Reunión Bienal de la RSEQ, Zaragoza, Spain.

- **Quantum effects of forbidden spin transitions in reactions between organic substrates and O₂** *(oral)*
  14th Young Researchers in Atomic and Molecular Physics Conf. RSEQ, Madrid, Spain.

## 2022

- **Quantum dynamics of the addition of O₂ to organic substrates** *(poster — Award)*
  MD-GAS Cost Action, Madrid, Spain.

- **Quantum dynamics of the addition of O₂ to organic substrates** *(poster)*
  High Dimensional Quantum Dynamics (HDQD), Groningen, Netherlands.

  ---

## Conference Gallery

<div style="max-width: 700px; margin: 0 auto; text-align: center;">

  <!-- Carousel container -->
  <div style="position: relative; overflow: hidden; border-radius: 10px;">

    <!-- Slides -->
    <div class="conf-slide" style="display: block;">
      <img src="/images/bologna2.jpg" style="width:100%; border-radius:10px;" />
      <p style="margin-top: 8px; font-style: italic; color: #555;">
        COSY Cost Action General Meeting, Bologna, Italy — 2025
      </p>
    </div>

    <div class="conf-slide" style="display: none;">
      <img src="/images/foto-siena.jpeg" style="width:100%; border-radius:10px;" />
      <p style="margin-top: 8px; font-style: italic; color: #555;">
      15th Symposium on Computing π-Conjugated Compounds, University of Siena, Italy
      </p>
    </div>

    <div class="conf-slide" style="display: none;">
      <img src="/images/foto-imampc.jpeg" style="width:100%; border-radius:10px;" />
      <p style="margin-top: 8px; font-style: italic; color: #555;">
        13th International Meeting on Atomic and Molecular Physics and Chemistry, Warsaw, Poland
      </p>
    </div>

     <div class="conf-slide" style="display: none;">
      <img src="/images/foto-wroclaw.jpeg" style="width:100%; border-radius:10px;" />
      <p style="margin-top: 8px; font-style: italic; color: #555;">
        COSY Cost Action General Meeting, Wroclaw, Poland
      </p>
    </div>

     <div class="conf-slide" style="display: none;">
      <img src="/images/foto-j2ifam.jpeg" style="width:100%; border-radius:10px;" />
      <p style="margin-top: 8px; font-style: italic; color: #555;">
        XV Conference of Young Researchers in Atomic and Molecular Physics, University of Valencia, Spain 
      </p>
    </div>



  </div>

  <!-- Navigation buttons -->
  <div style="margin-top: 14px;">
    <button onclick="moveSlide(-1)"
      style="padding: 8px 20px; margin: 0 8px; border: none; border-radius: 6px;
             background: #1a5276; color: white; font-size: 18px; cursor: pointer;">
      &#8592;
    </button>
    <button onclick="moveSlide(1)"
      style="padding: 8px 20px; margin: 0 8px; border: none; border-radius: 6px;
             background: #1a5276; color: white; font-size: 18px; cursor: pointer;">
      &#8594;
    </button>
  </div>

  <!-- Slide counter -->
  <p id="slide-counter" style="margin-top: 8px; color: #888; font-size: 0.9em;">1 / 3</p>

</div>

<script>
  let currentSlide = 0;
  const slides = document.querySelectorAll('.conf-slide');

  function moveSlide(direction) {
    slides[currentSlide].style.display = 'none';
    currentSlide = (currentSlide + direction + slides.length) % slides.length;
    slides[currentSlide].style.display = 'block';
    document.getElementById('slide-counter').textContent =
      (currentSlide + 1) + ' / ' + slides.length;
  }
</script>

