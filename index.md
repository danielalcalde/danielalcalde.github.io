---
title: Daniel Alcalde Puente
---
<link href="https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500&family=Lora&display=swap" rel="stylesheet">

## About me
I have had many interests that have come and gone throughout my life, but understanding complex systems and programming are two long-standing passions of mine that have stayed over the years. I pursued my interest in physics at the Ruhr-Universität Bochum, where I earned a bachelor's and master's degree in physics with a focus on computational solid-state physics and machine learning. During this time, I fell in love with Python and used it not only for my research but also for small projects in my spare time, from programming an Alexa skill to building machine learning pipelines to automate boring tasks. After that, I completed a PhD in Computational Physics with a focus on learning algorithms and Quantum Computing. Currently, I am searching for a Data Scientist position in the Bonn-Cologne Area.

## Open Source Projects

<style>
.project {
  display: flex;
  align-items: center;
  margin-bottom: 1.2em;
}

.project-link {
  display: inline-block;
  width: 200px;
  text-decoration: none;
  color: inherit;
}

.project-logo {
  width: 200px;
  text-align: center;
  font-family: 'Amatic SC', cursive;
  font-size: 1.8em;
  color: #444;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100px;
}

.project-desc {
  margin-left: 1em;
  font-family: 'Poppins', sans-serif;
  font-size: 0.9em;
  line-height: 1.4em;
  max-width: 600px;
}

.project-link:hover .project-logo {
  text-decoration: underline;
}

/* Slightly smaller text for entries without a logo */
.project:not(:has(img)) .project-desc {
  font-size: 0.85em;
  line-height: 1.4em;
}

/* Responsive layout */
@media (max-width: 700px) {
  .project {
    flex-direction: column;
    align-items: flex-start;
  }
  .project-link, .project-logo {
    width: 100%;
    text-align: left;
    margin-bottom: 0.3em;
  }
  .project-desc {
    margin-left: 0;
    max-width: 100%;
  }
}
</style>

<div class="project">
  <a class="project-link" href="https://github.com/danielalcalde/encap">
    <img
      src="https://user-images.githubusercontent.com/53435922/217352989-c400e86c-31e0-40cb-a734-004e5994dda8.svg"
      alt="encap logo"
      style="width:200px; vertical-align:middle;"
    />
  </a>
  <div class="project-desc">
    A simple tool to keep track of computational experiments.
  </div>
</div>

<div class="project">
  <a class="project-link" href="https://github.com/danielalcalde/AutoMeetingNotes">
    <div class="project-logo"><strong>AutoMeeting<br>Notes</strong></div>
  </a>
  <div class="project-desc">
    A Python web UI for generating speaker-diarized meeting transcriptions from audio recordings.
  </div>
</div>

<div class="project">
  <a class="project-link" href="https://danielalcalde.github.io/apalis/">
    <img
      src="apalis/_static/apalislogo.svg"
      alt="apalis logo"
      style="width:200px; vertical-align:middle;"
    />
  </a>
  <div class="project-desc">
    A Python library for parallel computing with little overhead.
  </div>
</div>

## Physics Packages

<div class="project">
  <a class="project-link" href="https://github.com/NeTeNeSyQuMa/ParallelGradient.jl">
    <div class="project-logo"><strong>ParallelGradient.jl</strong></div>
  </a>
  <div class="project-desc">
    Fast, parallel automatic differentiation in Julia using distributed and threaded computing. Optimized for reduced data transfer and supports scalar and Flux models.
  </div>
</div>

<div class="project">
  <a class="project-link" href="https://github.com/NeTeNeSyQuMa/mVQE">
    <div class="project-logo"><strong>mVQE</strong></div>
  </a>
  <div class="project-desc">
    Implementation of Measurement and Feedback-Based Variational Circuits.
  </div>
</div>

<div class="project">
  <a class="project-link" href="https://github.com/NeTeNeSyQuMa/QuantumNaturalGradient.jl">
    <div class="project-logo"><strong>QuantumNaturalGradient.jl</strong></div>
  </a>
  <div class="project-desc">
    Efficient and scalable natural gradient Julia library for time evolution and optimization.
  </div>
</div>

<div class="project">
  <a class="project-link" href="https://github.com/NeTeNeSyQuMa/QuantumNaturalfPEPS.jl">
    <div class="project-logo"><strong>QuantumNaturalfPEPS.jl</strong></div>
  </a>
  <div class="project-desc">
    A Julia package for simulating and optimizing quantum many-body systems using the PEPS (Projected Entangled Pair States) framework via Stochastic Natural Gradient.
  </div>
</div>
